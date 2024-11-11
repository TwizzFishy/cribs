# CRIBS README

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Roadmap](#roadmap)
7. [Contribution Guidelines](#contribution-guidelines)
8. [License](#license)

---

## Introduction

**CRIBS** is a unique app designed to simplify and streamline the process of short-term rentals by creating connections between renters and landlords in a fun, engaging way. Inspired by dating apps, CRIBS offers a swiping mechanism where renters can browse through property listings and swipe right on properties they love. Similarly, landlords can swipe right on potential renters who catch their interest. Once both sides express mutual interest, they match and can begin communicating.

Our goal is to make short-term rentals convenient, reliable, and trustworthy through interactive features such as a rating system and planned implementation of photo ID verification for added security.

---

## Features

- **Swipe to Match**: Renters swipe right on properties they like; landlords do the same with tenant profiles.
- **Matching System**: Mutual interest leads to a match, unlocking direct communication between parties.
- **Rating System**: Ratings for both properties and renters to promote accountability and trust.
- **User Profiles**: Create comprehensive profiles as a renter or landlord, complete with photos and key details.
- **Messaging**: Secure messaging for matched users.
- **Photo ID Verification (Planned)**: Future feature to enhance trust and security in the rental process.
- **Intuitive Design**: User-friendly interface designed using Figma, ensuring easy navigation.

---

## Technologies Used

- **Backend**: Django (including database management)
- **Frontend**: HTML, CSS, JavaScript
- **Prototype Design**: Figma

---

## Installation

### Prerequisites

Before you begin, make sure you have the following installed on your system:
- Python 3.x
- Django framework
- Node.js (optional, for additional frontend dependencies)

### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/username/cribs.git
   cd cribs


2. Create and activate virtual enviroment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


3. Install required dependencies:
pip install -r requirements.txt

4. Run database migrations:
python manage.py migrate

5. Start development server:
python manage.py runserver
Usage



## For Renters
Create and customize your profile with your preferences and required information.
Browse available properties.
Swipe right on properties you are interested in and left on those you are not.
When a landlord swipes right on you too, you both match and can start a conversation.

## For Landlords
List your property by creating a detailed profile.
Browse through potential renters’ profiles.
Swipe right on renters who meet your criteria.
Begin communicating with matches to finalize rental agreements.

ROADMAP:
Photo ID Verification: Planned feature to enhance user trust and security.
Enhanced Search and Filtering: Customizable options to improve property and renter discovery.
Improved Rating System: Advanced features for better feedback and ratings management.