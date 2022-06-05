# MageTail: Magento 2 + Tailwind CSS Theme (Proof of concept)

This is a try out project to integrate Tailwind CSS into Magento 2. It works and was quite easy to achieve to get it working.

## Idea behind project

I was playing with this idea for a while now. Since then Hyva (https://hyva.io/) came out. Hyva does the same with allot more. It is a complete overhaul of the frontend of Magento 2 including change of JS stack. So if you are looking for something for production, go check it out. The idea behind this project was just have Luma with the magic of Tailwind CSS. 

## Steps to achieve goal

1. Don't load original Luma CSS
2. Incorporate Tailwind CSS into Magento 2
3. Leave html id's and classes as they are so the JS keeps working as expected
4. Restyle complete frontend with Tailwind CSS

## WIP

1, 2 and 3 are done. The most work is of course the fourth bullet point. This is where I left off (for now).

## Usage

- clone into `app\design\frontend\Aqm\Magetail`
- run `npm install`
- run `npx tailwindcss -i ./web/css/main.css -o ./web/css/tailwind.css --watch` from the theme root

## Author

- Akif Gumussu (info@aquive.nl) 
