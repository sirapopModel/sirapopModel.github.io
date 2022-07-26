---
layout: default
title: Arduino_LED.md
---
# Pattern A

## Step 1. Initially, only one LED (at index=0) is ON, and the rest of the LEDs are OFF. 

## Step 2. The position of the ON LED should be moved to the next in a circular manner in a fixed time interval and then repeat

<p align="center">
  <img src="/photo/Arduino_Pattern/PatternA.png" alt="Cute_boy" width="800" height="600"/>
 </p>

# PatternB

## Step 1. Initially, all LEDs are OFF. 

## Step 2. Turn on the LEDs one by one with a time delay, starting at index=0 until all LEDs are ON.

## Step 3. If all LEDs are ON, turn off LEDs one by one starting at index=n-1,  where n is the total number of LEDs, until all LEDs are OFF, and repeat Steps 2-3.

<p align="center">
  <img src="/photo/Arduino_Pattern/PatternB.png" alt="Cute_boy" width="800" height="600"/>
 </p>

# PatternC

## Step 1. Initially, all LEDs are OFF.

## Step 2. Turn on the first LED by increasing the duty cycle of the PWM signal driving the LED, until the LED is fully ON.

## Step 3. Repeat Step 2 with the next LED until all LEDs are fully ON.

## Step 4. If all LEDs are ON, turn off LEDs one-by-one by decreasing the duty cycles of the PWM signals until all LEDs are OFF and repeat Steps 2-4.

<p align="center">
  <img src="/photo/Arduino_Pattern/PatternC.png" alt="Cute_boy" width="800" height="600"/>
 </p>

# PatternD

## Step 1. Initially, all LEDs are OFF. 

## Step 2. Turn on the first 4 LEDs using PWM signals, each with different duty cycles (e.g. 100%, 50%, 25%, 10%), and the rest of the LEDs are OFF.

## Step 3. Move the positions of ON LEDs to the left by one position in a circular manner and repeat Step 3.

<p align="center">
  <img src="/photo/Arduino_Pattern/PatternD_1.png" alt="Cute_boy" width="800" height="600"/>
 </p>
 
 <p align="center">
  <img src="/photo/Arduino_Pattern/PatternD_2.png" alt="Cute_boy" width="800" height="600"/>
 </p>
