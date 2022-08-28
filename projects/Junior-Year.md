---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Junior-Year"
date: August 28th, 022
published: true
labels:
  - Goals
  - Classes
  - Graduation
summary: "Junior-Year is a combination of schedules, goals, and graduation requirements to ensure I follow all the steps to graduate on time."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Junior-Year will allow myself to check my credit requirement progress thus far and allow me set goals based on the work I have completed so far. 

For this project, I wanted to make sure I made all the right steps towards graduation. Being organized and knowing your requirements for graduation is essentail for anyone to graduate on time or even earlier. 

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
