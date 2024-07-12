// Database Schema
const Dish = {
  name: String,
  description: String,
  price: Number,
  published: Boolean
};

// API Endpoints
const express = require('express');
const app = express();

app.get('/dishes', (req, res) => {
  // Get all dishes
});

app.post('/dishes', (req, res) => {
  // Create a new dish
});

app.put('/dishes/:id', (req, res) => {
  // Update a dish by ID
});

app.delete('/dishes/:id', (req, res) => {
  // Delete a dish by ID
});

// Front-end Dashboard (using React)
import React, { useState, useEffect } from 'react';

const Dashboard = () => {
  const [dishes, setDishes] = useState([]);

  useEffect(() => {
    // Fetch dishes from API
  }, []);

  const togglePublishStatus = (id) => {
    // Toggle the published status of a dish
  };

  return (
    <div>
        <div key={dish.id}>
          <h3>Dish.Jeera Rice</h3>
          <p>"Dish": "1",</p>
          <p>"imageUrl": "https://nosh-assignment.s3.ap-south-1.amazonaws.com/jeera-rice.jpg",
"isPublished": true</p>
          <button onClick={() => togglePublishStatus(dish.id)}>
            {dish.published ? 'Unpublish' : 'Publish'}
          </button>
        </div>
  }
<div>
        <div key={dish.id}>
          <h3>Dish.Paneer Tikka</h3>
          <p>"Dish": "2",</p>
          <p>"imageUrl": "https://nosh-assignment.s3.ap-south-1.amazonaws.com/Paneer Tikka.jpg",
"isPublished": true</p>
          <button onClick={() => togglePublishStatus(dish.id)}>
            {dish.published ? 'Unpublish' : 'Publish'}
          </button>
        </div>
<div>
        <div key={dish.id}>
          <h3>Dish.Rabdi</h3>
          <p>"Dish": "3",</p>
          <p>"imageUrl": "https://nosh-assignment.s3.ap-south-1.amazonaws.com/Rabdi.jpg",
"isPublished": true</p>
          <button onClick={() => togglePublishStatus(dish.id)}>
            {dish.published ? 'Unpublish' : 'Publish'}
          </button>
        </div>
 <div key={dish.id}>
          <h3>Dish.Cikken Biriyani</h3>
          <p>"Dish": "4",</p>
          <p>"imageUrl": "https://nosh-assignment.s3.ap-south-1.amazonaws.com/Cikken Biryani.jpg",
"isPublished": true</p>
          <button onClick={() => togglePublishStatus(dish.id)}>
            {dish.published ? 'Unpublish' : 'Publish'}
          </button>
        </div>
 <div key={dish.id}>
          <h3>Dish."Alfredo Pasta",</h3>
          <p>"Dish": "5",</p>
          <p>"imageUrl": "https://nosh-assignment.s3.ap-south-1.amazonaws.com/"Alfredo Pasta",.jpg",
"isPublished": true</p>
          <button onClick={() => togglePublishStatus(dish.id)}>
            {dish.published ? 'Unpublish' : 'Publish'}
          </button>
        </div>
