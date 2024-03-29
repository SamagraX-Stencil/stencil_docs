---
title: Overview
sidebar_label: Overview
---



<head>
  <title> Overview </title>
  <meta
    name="description"
    content="your meta content goes here"
  />
</head>



## Streamlining Bot Creation with a Config-Based Approach

The Config-based approach significantly simplifies the bot creation process by enabling easy creation and updates through a straightforward form within an admin panel.

Before delving into the details, let's first understand the definitions of `atom` and `molecule`.

## Atom

An `atom` is a basic building block, representing an independent component that can be used alone or combined with other atoms to form more complex structures, termed as molecules. Examples include Input fields, Buttons, and Typography elements, each serving as a fundamental part of user interface design.

## Molecule

A `molecule` is a compound component made up of various atoms. It represents a more intricate UI element designed to fulfill a specific function within an application's interface. For example, a Login Page or an OTP (One-Time Password) Page, each composed of multiple atoms to provide a comprehensive and functional unit.

## Process Overview

The process involves several steps:

### Step 1: Create a Molecule

Start by designing a molecule in the [molecule repository](https://github.com/SamagraX-Stencil/ui-templates/tree/dev/src/molecules). When doing so, consider the different configurations and customizations that could be applied to make the molecule versatile and visually appealing. For instance, a Login molecule might offer customization options like label texts variations, theme choices, and other adjustable properties to align with your application's design and functional needs.

### Step 2: Define Molecule Configuration

Specify the configuration options for your molecule that can be altered via the admin panel. For a `Navbar` molecule, for example, configuration properties might include `brandName`, various `logos`, and their placements, allowing for customization to fit the application's branding and design schema.

### Step 3: Configure the Admin Panel

Incorporate the newly created molecule and its configuration options into the admin panel. This step involves setting up the admin panel to display input fields for all the configurable properties of the molecule, thereby simplifying the customization process.

### Step 4: Render the Configuration Form

Utilize the defined configuration to render form elements within the admin panel. This allows for the dynamic alteration of the molecule's properties, enabling administrators to customize the molecule according to specific needs directly from the admin panel.

### Step 5: Generate the Final Configuration

The final step involves generating the ultimate configuration from the admin panel inputs. This configuration is what customizes the bot, making it ready for deployment with its newly defined functionalities and appearance.

Adopting this Config-based approach facilitates a flexible and efficient way to customize bots, ensuring they meet specific requirements with ease.
