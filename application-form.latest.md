# CoCreate Pitch Application Form

Updated: 2026-05-07

This document reflects the current live application form at `https://alibabacocreate.com/pitch/apply-form`. Use it as the source of truth for form fields, options, required flags, conditional rules, agreements, and long-answer guidance.

## Status Rules

- `Required: yes` means the applicant must answer the question.
- `Required: no` means the question is optional.
- `Required: conditional` means the question appears only when its condition applies.
- `Affects future questions: yes` means the answer controls later conditional questions.

## Application Form

### Step 1 - Identification & Track Selection

#### Email Address

- Section: Identification
- Type: input
- Required: yes

#### What is your full name (first and last)?

- Section: Identification
- Type: input
- Required: yes

#### Where is or would be your company located (Region)?

- Section: Location
- Type: searchable select
- Required: yes
- Choices:
  - Full live region/country list from the website (250 options).

#### Which track would you like to apply for?

- Section: Track Selection
- Type: select
- Required: yes
- Affects future questions: yes
- Choices:
  - General SMEs Track: for established small and medium businesses ready to scale.
  - 0-to-1 Startup Track: for founders using Accio Work to bring raw ideas to life.
  - Students Track: for current students building next-generation products.

#### Which Finals event would you like to attend if selected?

- Section: Competition Location
- Type: select
- Required: yes
- Affects future questions: yes
- Choices:
  - Los Angeles Finals: September 9-10, 2026
  - London Finals: November 19-20, 2026

#### In which university do you study? (Official English Name in Title Case)

- Section: Identification - conditional
- Type: input
- Required: conditional
- Conditional display:
  - Show only when `Which track would you like to apply for?` is `Students Track: for current students building next-generation products.`
- Placeholder:
  - Example: University of California, Los Angeles

#### What is your major or field of study?

- Section: Identification - conditional
- Type: select
- Required: conditional
- Conditional display:
  - Show only when `Which track would you like to apply for?` is `Students Track: for current students building next-generation products.`
- Choices:
  - Business
  - Engineering
  - Computer Science
  - Design
  - Sciences (Physical/Life)
  - Humanities
  - Social Sciences
  - Arts
  - Law
  - Medicine & Health
  - Other

### Step 2 - Presence / Verification

#### Please provide the link to your personal LinkedIn profile.

- Section: Online Presence
- Type: input
- Required: no

### Step 3 - Business Profile

#### How many followers do you personally or your brand currently have across your primary social media platforms?

- Section: Business Profile
- Type: select
- Required: yes
- Choices:
  - under 1k followers
  - 1k to 10k followers
  - over 10k followers

#### Do you have, or plan to develop, any patents, trademarks, or proprietary formulations?

- Section: Defensibility
- Type: radio
- Required: yes
- Choices:
  - Yes
  - No

#### What is your current or target industry?

- Section: Business Profile
- Type: select
- Required: yes
- Choices:
  - Apparel & Accessories
  - Consumer Electronics
  - Beauty
  - Rubber & Plastics
  - Home & Garden
  - Jewelry, Eyewear, Watches & Accessories
  - Sports & Entertainment
  - Vehicles & Accessories
  - Home Appliances
  - Packaging & Printing
  - Construction & Real Estate
  - Chemicals
  - Mother, Kids & Toys
  - Shoes & Accessories
  - Gifts & Crafts
  - Luggage Bags & Cases
  - Furniture
  - Pet Supplies
  - Personal Care & Household Cleaning
  - Food & Beverage
  - Renewable Energy
  - Industrial Machinery
  - Other

#### What specific type of product does your company sell or plan to sell?

- Section: Business Profile
- Type: select
- Required: yes
- Choices:
  - Physical Products - Tangible goods that can be sold/distributed online
  - Digital Products - Software, apps, or digital solutions
  - Hardware + Software - Physical devices with digital components
  - Digital Services - Online platforms, marketplaces, or service delivery
  - Professional Services - Consulting, advisory, or traditional services

#### Do you have a company?

- Section: Business Profile
- Type: select
- Required: yes
- Affects future questions: yes
- Choices:
  - Yes
  - No

### Step 3 - Business Profile - conditional

#### What is the registered name of your company?

- Section: Business Profile - conditional
- Type: input
- Required: conditional
- Conditional display:
  - Show only when `Do you have a company?` is `Yes`.

#### What stage is your company currently in?

- Section: Business Profile - conditional
- Type: select
- Required: conditional
- Conditional display:
  - Show only when `Do you have a company?` is `Yes`.
- Choices:
  - Idea/Concept
  - Prototype/MVP
  - Product launched
  - Revenue generating
  - Scaling
  - Exit/acquisition

#### What is your company's current annual revenue (in USD)?

- Section: Business Profile - conditional
- Type: select
- Required: conditional
- Conditional display:
  - Show only when `Do you have a company?` is `Yes`.
- Choices:
  - Pre-revenue
  - $1-$100K
  - $100K-$1M
  - $1M-$10M
  - $10M+

#### Can you share your official website URL and/or primary business social media links (e.g., LinkedIn, Instagram, TikTok).

- Section: Business Profile - conditional
- Type: input
- Required: conditional
- Conditional display:
  - Show only when `Do you have a company?` is `Yes`.

#### If you were to start a company, what would you call it?

- Section: Business Profile - conditional
- Type: input
- Required: conditional
- Conditional display:
  - Show only when `Do you have a company?` is `No`.

### Step 4 - Long-Form Content

#### Please describe your product.

- Section: Long-Form
- Type: textarea
- Required: yes
- Notes:
  - Friendly reminder: leverage Accio Work to research and refine your answer.
- Suggested answer structure:
  - What is the product (or planned product) and the market problem it solves?
  - Who is your target buyer?
  - What are your unique advantages over competitors?

#### Please share your business story.

- Section: Long-Form
- Type: textarea
- Required: no
- Suggested answer structure:
  - What inspired you to start this business / develop this idea?
  - Key milestones since founding.
  - Recognition received, such as press features, industry awards, or competition results.

#### What supply chain challenges do you face today, and how do you see your sourcing evolving as your business scales?

- Section: Long-Form
- Type: textarea
- Required: no

#### Why are you applying, and how will the prize help your business?

- Section: Long-Form
- Type: textarea
- Required: no

### Step 5 - Alibaba Ecosystem

#### Are you an existing buyer on Alibaba.com?

- Section: Alibaba Ecosystem
- Type: select
- Required: yes
- Affects future questions: yes
- Choices:
  - Yes
  - No

#### Please share your Alibaba.com member ID.

- Section: Alibaba Ecosystem - conditional
- Type: input
- Required: conditional
- Conditional display:
  - Show only when `Are you an existing buyer on Alibaba.com?` is `Yes`.

## Agreements

### Terms & Conditions and Privacy Policy Agreement

- Type: checkbox
- Required: yes
- Text:
  - By registering for the competition, the participant agrees to the CoCreate Pitch Terms and Conditions, CoCreate Pitch Privacy Policy, and Alibaba.com Privacy Policy.
  - Please read the above terms carefully. Checking the box indicates that you agree to all contents.
- Checkbox label:
  - I have read and agree to the above terms

### Promotional communications consent

- Type: checkbox
- Required: no
- Checkbox label:
  - I agree to receive announcement, promotions and news from CoCreate via email and phone/SMS.

### Partner marketing consent

- Type: checkbox
- Required: no
- Text:
  - I consent to Alibaba.com sharing my email and business information with Alibaba.com's Partners for marketing purposes via email in accordance with CoCreate Pitch Privacy Policy, Accio Privacy Policy, and Alibaba.com Privacy Policy.
