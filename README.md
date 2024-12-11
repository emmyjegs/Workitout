# WorkITout Application Deployment on Kubernetes

**WorkITout** is a fitness management application designed to simplify and enhance the fitness journey for individuals and groups. 
The application is built for deployment on Kubernetes, ensuring scalability, reliability, and easy access via a public URL.


## Features

- **Workout Tracking**: Log and monitor your fitness activities and progress.
- **Group Workouts**: Create group challenges to motivate and engage with friends.
- **Customizable Plans**: Design personalized workout plans suited to your needs.
- **Notifications**: Get timely reminders and updates for your scheduled activities.
- **Cloud Deployment**: Deploy and manage the application seamlessly using Kubernetes.

- ## Deployment

This document guides you through deploying the Workitout application on **Azure Kubernetes Service (AKS)** and making it accessible via a public URL.

---

## Installation

### 1. Set Up the AKS Cluster

**Create a Resource Group**:
   ```bash
   az group create --name WorkITout --location eastus
