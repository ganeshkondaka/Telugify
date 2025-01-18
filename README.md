# Telugify - Telugu Error Messages for Developers 🚀

`Telugify` is a fun and expressive NPM library that converts HTTP error codes into meaningful, quirky, and humorous error messages in **Telugu**! Make your application logs more relatable for Telugu-speaking developers. 🎉

# Telugify 🌟

[![npm version](https://img.shields.io/npm/v/telugify.svg)](https://www.npmjs.com/package/telugify)
[![License](https://img.shields.io/npm/l/telugify.svg)](https://github.com/yourusername/telugify/blob/main/LICENSE)

Convert HTTP error messages to friendly Telugu responses! Perfect for adding a regional touch to your Node.js applications.

## Features ✨

- Converts common HTTP error codes to Telugu messages
- Easy to integrate
- TypeScript friendly
- Engaging error messages

## Installation 📦

```bash
npm install telugify
```


Usage 💻
Here’s how you can use the telugify library in your project:

Example:------------------

```bash
// Import the Telugify library
const { telugify } = require('telugify');

// Simulate an error object with a response status
const error = {
  response: {
    status: 404, // Example: HTTP 404 error},};

// Pass the error object to telugify
telugify(error); 

// Output:
// "ఏమిటి రా! {resource} ఇక్కడ ఎక్కడా కనబడట్లేదు రా!"

```

------------------------------------------------------

Status Code	Message :--------------

```bash

400	ఏరా! నువ్వు పంపిన రిక్వెస్ట్ అర్థం కావట్లేదురా, సరిగా చెయ్యి!
401	సరే రా, లాగిన్ చేయలేదు కదురా, అందుకే యాక్సెస్ లేదు!
403	ఏరా! నువ్వు ఈ జాగా అడుగు పెట్టలేరు రా, అడ్డా లేదురా!
404	ఏమిటి రా! {resource} ఇక్కడ ఎక్కడా కనబడట్లేదు రా!
405	ఈ రూట్ మీద {method} చేయలేం రా, డాక్యుమెంటేషన్ చూడరా!
408	ఏం సార్! నీ రిక్వెస్ట్ టైమ్ అవుట్ అయిపోయింది రా, ఇంకోసారి ట్రై చెయ్యి.
409	ఒక్కటే డేటాను రెండు సార్లు పోగొట్టడానికే ప్రయత్నించావా రా?
422	ఏరా! సరిగ్గా డేటా పంపి చెయ్యరా! ఇక్కడా తలకిందులు అయిపోయింది!
429	అబ్బో! సర్వర్ మీద బాగా హడావిడి చేసావురా, కాస్త ఆగు!
500	సర్వర్ గుండెల మీద భారంగా ఉంది రా, ఇబ్బంది పెట్టవద్దు!
502	సర్వర్ నుంచి మంచి సమాధానం రాలేదురా, ఇంకోసారి ప్రయత్నించు!
503	ఇప్పుడు సర్వర్ పనిలో లేకపోతున్నది రా, కాస్త సమయం తీసుకో!
504	సర్వర్ సమయం ఎక్కువ తీసుకుంటున్నది రా, ఇక్కడ ఇంకోసారి చెక్ చేయు!

```

Contributing 🤝

Want to contribute to Telugify? Feel free to:--------------------

- Fork the repository.
- Create a new branch.
- Add your changes and create a pull request.
- License 📝
- This project is licensed under the MIT License.

Feel free to open issues or submit PRs to improve Telugify. Your support and feedback are appreciated! ❤️
