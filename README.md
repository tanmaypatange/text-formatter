# Text Formatter: Case-Preserving Contractions Manager

A web application for converting between contractions and their expanded forms while preserving original capitalization. Handle text transformations with proper case maintenance and real-time comparison features.

**Live Demo:** [https://tanmaypatange.github.io/text-formatter/](https://tanmaypatange.github.io/text-formatter/)

## Features

### Core Functionality
- Bidirectional conversion between contractions and expanded forms
- Case-preserving transformations:
  - UPPERCASE: "YOU'RE" → "YOU ARE"
  - Title Case: "You're" → "You Are"
  - lowercase: "you're" → "you are"
- Supports 50+ common English contractions (full list below)

## Complete Contractions List

| Contraction    | Expanded Form        |
|----------------|----------------------|
| how're         | how are              |
| how's          | how is               |
| what're        | what are             |
| where're       | where are            |
| when're        | when are             |
| why're         | why are              |
| who're         | who are              |
| that're        | that are             |
| there're       | there are            |
| they're        | they are             |
| you're         | you are              |
| we're          | we are               |
| ain't          | am not               |
| aren't         | are not              |
| can't          | cannot               |
| could've       | could have           |
| couldn't       | could not            |
| didn't         | did not              |
| doesn't        | does not             |
| don't          | do not               |
| hadn't         | had not              |
| hasn't         | has not              |
| haven't        | have not             |
| he'd           | he would             |
| he'll          | he will              |
| he's           | he is                |
| how'd          | how did              |
| how'll         | how will             |
| I'd            | I would              |
| I'll           | I will               |
| I'm            | I am                 |
| I've           | I have               |
| isn't          | is not               |
| it's           | it is                |
| let's          | let us               |
| might've       | might have           |
| must've        | must have            |
| mustn't        | must not             |
| needn't        | need not             |
| oughtn't       | ought not            |
| shan't         | shall not            |
| she'd          | she would            |
| she'll         | she will             |
| she's          | she is               |
| should've      | should have          |
| shouldn't      | should not           |
| that's         | that is              |
| there's        | there is             |
| they'd         | they would           |
| they'll        | they will            |
| they've        | they have            |
| wasn't         | was not              |
| we'd           | we would             |
| we'll          | we will              |
| we've          | we have              |
| weren't        | were not             |
| what'll        | what will            |
| what's         | what is              |
| what've        | what have            |
| where'd        | where did            |
| where's        | where is             |
| who'd          | who would            |
| who'll         | who will             |
| who's          | who is               |
| why'd          | why did              |
| why'll         | why will             |
| why's          | why is               |
| won't          | will not             |
| would've       | would have           |
| wouldn't       | would not            |
| y'all          | you all              |
| you'd          | you would            |
| you'll         | you will             |
| you've         | you have             |

## Usage Instructions

1. **Input Text**
   - Paste or type text into the left (editable) panel
   - Automatic synchronization with output panel

2. **Transformations**
   - Click "Remove Contractions" to expand all contractions
   - Click "Add Contractions" to convert to contracted forms
   - Use "Revert" to restore original text

3. **Comparison**
   - Click "Compare Text" to highlight differences
   - Red highlights: Removed content
   - Green highlights: Added content

4. **Output Management**
   - Copy transformed text with "Copy Text" button
   - Reset both panels with "Reset" button

## Installation

```bash
git clone https://github.com/tanmaypatange/text-formatter.git
cd text-formatter
