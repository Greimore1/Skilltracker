# SkillTracker

## Overview
SkillTracker is a comprehensive professional development and skill management application designed to help individuals and teams track, analyze, and improve their technical skills.

## Features
- User authentication and profile management
- Skill tracking and proficiency assessment
- Project portfolio management
- Skills gap analysis
- Personalized learning recommendations

## Prerequisites
- Ruby 3.1.2
- Rails 7.0.4
- PostgreSQL 13+
- Docker (optional)

## Local Development Setup

### 1. Clone the Repository
```bash
git clone https://github.com/[YOUR_USERNAME]/skilltracker.git
cd skilltracker
```

### 2. Install Dependencies
```bash
bundle install
yarn install
```

### 3. Database Setup
```bash
rails db:create
rails db:migrate
```

### 4. Run the Application
```bash
rails server
```

## Running Tests
```bash
bundle exec rspec
```

## Docker Deployment
```bash
docker-compose up --build
```

## Environment Configuration
Create a `.env` file in the project root with the following variables:
```
DATABASE_URL=postgresql://username:password@localhost/skilltracker
RAILS_ENV=development
SECRET_KEY_BASE=your_secret_key
```
