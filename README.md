# D-AF-Brand-Suggestions--Utilizing-Chinese-Sentiment-Analysis

This is a student term project in Global Brand Management, National Taiwan University

## Quick Links

- [Global Brand Management Term Project](https://github.com/brianCHUCHU/Store-Sales---Time-Series-Forecasting/blob/main/Store%20Sales%20-%20Time%20Series%20Forecasting.pdf): For detailed documentation in formal PDF format.
- [Slides](https://github.com/brianCHUCHU/Store-Sales---Time-Series-Forecasting/blob/main/Slides.pdf): For presentation slides in PDF format.

## Project Overview

This project examines the brand management strategies of D+AF, a Taiwanese handcrafted women's shoe brand. The study includes a qualitative analysis of the brand's strengths and weaknesses, followed by a detailed quantitative analysis using sentiment analysis and word cloud techniques. Based on the findings, strategic solutions are proposed to enhance the brand's market position.

## File Structure

### 1. Brand Introduction
D+AF is a handmade women's shoe brand focused on design aesthetics and fashion. Founded in 2005 by Zhang Shiqi and his wife, it began on Yahoo's e-commerce platform and established its official website in 2015. The brand has since expanded to over 33 countries, opening its first physical store in Taipei in late 2020, and now has 11 stores across Taiwan, including 3 flagship stores. Known as the "fast fashion of women's shoes," D+AF releases new products almost every week, with over a thousand new styles annually and a diverse range of sizes from 34 to 43.

### 2. Qualitative Analysis of Brand Strengths and Weaknesses

#### (1) Strengths:
- Strong marketing capability and high brand awareness.
- Extensive social media advertising and collaborations with numerous YouTubers.
- High engagement on official social media platforms.
- Endorsements by Korean KOLs and idols such as Song Ji-a and Yeh Shu-hua.
- High cost-performance ratio with affordable, stylish designs.

#### (2) Weaknesses:
- Poor quality control and durability issues.
- Inconsistent comfort levels across products.
- Negative public relations image due to reported deletion of negative forum reviews.
- Decline in customer service quality and restrictive return policies.
- Incomplete in-store size ranges, leading to challenges for customers needing larger sizes.

### 3. Quantitative Analysis of Brand Strengths and Weaknesses

#### Analysis Method
We conducted sentiment analysis on forum comments, particularly focusing on a Dcard article titled "Don't buy D+AF anymore." The process involved aspect extraction, sentiment determination using the "uer/roberta-base-finetuned-jd-binary-chinese" model, and generating word clouds using CkipTagger and wordcloud packages.

**Aspect Extraction:**
Comments were manually tagged and encoded, covering categories like price, size, quality, service attitude, comfort, public relations, endorsements, and appearance.

**Sentiment Determination:**
Using a pre-trained BERT model, sentiment scores were calculated within the range of [-1, 1]. Positive comments were within [0, 1] and negative comments within [-1, 0).

**Word Cloud Analysis:**
Frequent terms from various comment categories were visualized, providing insights into common issues and perceptions.

#### Sentiment Analysis Results

- **Overall Comparison:** Quality and comfort are the most discussed aspects, with price-related comments often linked to quality and comfort issues.
- **Brand Comparison:** D+AF has notably higher negative sentiment scores compared to competitors, especially in quality and comfort.
- **Detailed Findings:**
  - **Quality:** Frequent mentions of "boots" and "sandals" indicate these styles often face quality issues, particularly with soles.
  - **Comfort:** Common issues include blisters and foot odor, with "boots," "sandals," and "loafers" frequently cited.
  - **Price:** Comments often compare D+AF to Taobao, suggesting perceived lower value for money.
  - **Size:** Positive comments highlight the brand's extensive size range, accommodating larger feet.
  - **Service Attitude:** Limited insightful data, but "staff" was a recurrent term.
  - **Public Relations:** High mentions of "advertising" and "marketing," with positive comments on the brand’s social media management.
  - **Endorsements:** Strong association with endorsements, particularly mentioning Yeh Shu-hua.
  - **Appearance:** Some comments indicate a "cheap look," suggesting potential dissatisfaction with design aesthetics.

#### Potential Biases and Future Directions
This analysis is limited to one Dcard article, potentially skewing towards negative sentiment. For more accurate insights, a broader data set across multiple articles is recommended. Further analysis can include IPA (Importance-Performance Analysis) or IPCA (Importance-Performance Competitive Analysis) to better understand strategic priorities.

### 4. Strategic Recommendations

#### Brand Value Orientation
We recommend treating comfort as a hygiene factor rather than a motivator, emphasizing non-blistering features initially for specific products, then potentially extending this strategy across the brand.

#### Key Strategies: Introducing a Comfort-focused Product Line
- **Short-term Strategy:** Launch a new product line emphasizing comfort while maintaining D+AF's aesthetic appeal. Priced slightly higher, this line aims to address comfort-related issues and recapture lost customers.
- **Long-term Strategy:** Adjust cost structure by reducing marketing expenses and reallocating funds to production and R&D, improving overall product comfort.

### 5. References
- Articles from United Daily News, Bella.tw, and other sources discussing D+AF's marketing strategies and digital transformation efforts.
