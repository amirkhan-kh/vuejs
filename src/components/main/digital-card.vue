<template>
   <div class="container">
    <div class="faq-container">
      <div class="faq-header">
        <h2>Digital Marketing FAQs</h2>
        <p>
          As a leading digital marketing agency, we are dedicated to providing
          comprehensive educational resources and answering frequently asked
          questions to help our clients.
        </p>
        <div class="faq-buttons">
          <button @click="moreQuestions">More Questions</button>
          <button @click="contactUs">Contact Us</button>
        </div>
      </div>
      <div class="faq-accordion">
        <div v-for="(faq, index) in faqs" :key="index" class="faq-item">
          <div class="faq-question" @click="toggleFaq(index)">
            <h3>{{ faq.question }}</h3>
            <span>{{ activeIndex === index ? '−' : '+' }}</span>
          </div>
          <div v-if="activeIndex === index" class="faq-answer">
            <p>{{ faq.answer }}</p>
          </div>
        </div>
      </div>
    </div>
   </div>
  </template>
  
<script>
  export default {
    data() {
      return {
        activeIndex: null,
        faqs: [
          {
            question: 'Why is digital marketing important for my business?',
            answer:
              'Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.',
          },
          {
            question: 'How can digital marketing help improve my website’s visibility?',
            answer: 'Digital marketing strategies such as SEO, social media marketing, and content marketing can improve your website’s visibility by making it more attractive to search engines and potential customers.',
          },
          {
            question: 'How long does it take to see results from digital marketing efforts?',
            answer: 'The time frame for seeing results varies based on the type of digital marketing strategy used and the industry, but most businesses start to see results within 3-6 months.',
          },
          {
            question: 'How do you measure the success of digital marketing campaigns?',
            answer: 'The success of digital marketing campaigns can be measured through various KPIs, including website traffic, conversion rates, click-through rates, and return on investment (ROI).',
          },
        ],
      };
    },
    methods: {
      toggleFaq(index) {
        this.activeIndex = this.activeIndex === index ? null : index;
      },
      moreQuestions() {
        // More questions button functionality
        console.log('More questions clicked');
      },
      contactUs() {
        // Contact us button functionality
        console.log('Contact us clicked');
      },
    },
  };
</script>
  
  <style scoped lang="scss">
.faq-container {
    margin: 90px 0px;
  padding: 60px;
  background-color: #ffffff;
  border-radius: 20px;
  display: flex;
  gap: 80px;
  width: 100%;

  .faq-header {
    width: 50%;
    h2 {
      font-size: 44px;
      font-weight: 600;
      margin-bottom: 40px;  
      line-height: 60px;
    }

    p {
      font-size: 16px;
      color: #666;
      line-height: 28px;
      margin-bottom: 40px;
    }
  }

  .faq-buttons {
    display: flex;
    gap: 20px;
    button {
      border: 1px solid #000;
      border-radius: 20px;
      cursor: pointer;
      font-size: 16px;
      width: 176px;
      height: 46px;
      &:nth-child(2) {
        border: none;
        background: transparent;
      }
    }
  }

  .faq-accordion {
    width: 50%;
  }

  .faq-item {
    border-bottom: 1px solid #8e8c8c;
    padding: 10px 0;

    .faq-question {
      display: flex;
      justify-content: space-between;
      align-items: center;
      cursor: pointer;
      font-weight: bold;
      font-size: 18px;
    }

    .faq-answer {
      margin-top: 10px;
      font-size: 16px;
      color: #333;
    }
  }
}
</style>
