---
name: Suggest Mantine extensions that are not listed on the website
about: Template for suggesting Mantine extensions that are not yet listed on Mantine
  Extensions Hub.
title: 'Suggest Mantine extension: <extension name>'
labels: enhancement
assignees: gfazioli

---

**Extension name**
Provide the full name of the Mantine extension.

---
body:
- type: input
  id: prevalence
  attributes:
    label: Bug prevalence
    description: "How often do you or others encounter this bug?"
    placeholder: "Whenever I visit the user account page (1-2 times a week)"
  validations:
    required: true
---  

**Short description**
Briefly describe what this extension does and what problem it solves.

**GitHub repository URL**
Paste the link to the GitHub repository for this extension.

**Additional notes (optional)**
Add any extra context, examples, or reasons why this extension should be listed.

**Quick way - fill the JSON below**

```json
{
  key: 'mantine-clock',
  title: 'Mantine Clock',
  href: 'https://gfazioli.github.io/mantine-clock',
  description:
    'Providing customizable analog Clock components and hooks (useClock, useClockCountDown) for real-time time management. Features global timezone support, countdown functionality, flexible formatting, and advanced controls for digital and analog timepieces.',
  date: '2025-07-10',
  url: 'https://gfazioli.github.io/mantine-clock/',
  published: true,
  repository: '@gfazioli/mantine-clock',
  video: 'https://github.com/user-attachments/assets/727a8634-28ee-4279-80b1-dcf2cb7f5961',
  author: 'gfazioli',
  image: 'https://github.com/gfazioli/mantine-clock/blob/master/logo.jpeg?raw=true',
  tags: ['time', 'clock', 'countdown', 'timezone', 'widget', 'hooks'],
}
```
