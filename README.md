# Dynamic Routes Lab

## Introduction

We've provided a basic `Item` class. Let's get more information on our items.

## Instructions

  1. Your application should only accept the `/items/<ITEM NAME>` route. Everything else should `404`
  2. If a user requests `/items/<Item Name>` it should return the price of that item
  3. IF a user requests an item that you don't have, then return a `400` and an error message
