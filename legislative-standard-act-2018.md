# Legislative Standard Act of 2018

## Part 1: Foundation
### Section 1: Preamble
This act lays out the legislative standard used in legislation across Arkovia. All Legislation in Arkovia MUST follow this standard. The act contains standards and guides on drafting legislation.

### Section 2: Purpose
The purpose of the Legislative Standard Act is to:
- Establish a legislative structure that allows easy referencing
- Establish a legislative structure that is easy to read & follow
- Establish a legislative structure that is machine-readable
- Create a guide that citizens can use to create legislation
- Allow easy modification and review.

## Part 2: Legislation Standard
### Section 1: Legislative Act Structure
#### Segment 1: Act Elements
The Act Elements are:

```markdown
# {{Title}}
  - Required
  - Example: "# Constitution Act"
  - The Title is the title of the Act in discusion, and should relate directly to it's contents.

## Part 1: Foundation
  - Required
  - Auto-Generated
  - The Foundation is a key part of legislation and is used to introduce and explain the purpose of the Act in discussion

### Section 1: Preamble
  - Required
  - The Preamble is a key section of legislation and is used to introduce and explain the Act in discussion

### Section 2: Purpose
  - Required
  - The Purpose is a key section of legislation and is used to explain the purpose of the Act in discussion

### Section ...
  - Optional
  - Used to add other sections to foundation

{{ Law }}
  - Required
  - The law section is added here
  - Parts start from 2 (Foundation is Part 1)
```

#### Segment 2: Act Heirarchy Structure
The Act Heirarchy Structure is as follows
```markdown
1. Title
2. Foundation
  1. Preamble
  2. Purpose
  3. {{ Optional Custom Sections }}
3. {{ Law }}
```
### Section 2: Law Guide
#### Segment 1: Introduction
In this section, we'll explain the law structure, elements and heirarchy used in the law of Arkovia

#### Segment 2: Law Elements
The Law Elements are the the various hierarchical elements deisnged to be easily followed, and easily referred. The Law Elements are used to implement the law.

```markdown
## Part {{ number }}: {{ title }}
- Title required
- Numbered
- Parts MUST contain atleast one section

### Section {{ number }}: {{ title }}
- Title required
- Numbered
- Sections MAY contain one or more segment
- Sections MAY contain text
- Sections MUST contain either segments or text

#### Segment {{ number }}{{ title ? ": " + title : ""}}
- Title optional
- Optional
- Numbered
- Segments MAY contain paragraph, rather than text
- Segments MAY contain text, rather than segments

#### Segment 2: Law Hierarchical Order
The Law Element Heirarchical Order is as follows:
```markdown
1. Part
  1. Section
    1. Text; OR
    2. Segment
      1. Text
```

#### Segment 3: Starting Part Number
The Part Numbers start from `2` as `Part 1` is the `Foundation`

### Section 3: Legislative Text Guide
#### Segment 1: Text Elements
Legislative text may include these elements:

1. Images
2. Text
3. Lists
4. Formatting

### Section 4: Examples
#### Segment 1: Markdown Example
```markdown
# Arkovia Constitution Act

## Part 1: Foundation
### Section 1: Preamble
We the citizens of Arkovia, choose to establish this constitution, in order to establish a nation & country which aims to: 
- Advance towards the future
- Advance in technology and infrastructure
- Create a simplistic & pragmatic approach to politics
- Create a true direct democracy
- Promote the welfare of citizens
- Secure the right to our universal-given land

### Section 2: Purpose
#### Segment 1: Purpose of the Constitution
The purpose of this constitution is to:
- Establish the existence our nation
- Establish a justice system
- Lay out the structure, function and powers of the Government of Arkovia
- Establish the Government Enchanced Government Institution (EGI) System
- Create a simple, pragmatic direct democracy

#### Segment 2: Purpose of Arkovia
- Create a Social Democracy and provide sufficient safety nets for citizens.
- Create a government where citizens have true democratic power
- Improve standards of living through technology and infrastructure

### Section 3: Interpretations
All questions regarding the interpretation of this Constitution shall be decided by the Genesis Council.

### Section 4: Definitions
\```
Citizen: Definition found in Citizenship Act
\```

### Section 5: Constitutional Amendments
#### Segment 1: Parts Subject to Amendments
All parts of this constitution and it's protected acts are subject to change unless explicitly stated.

#### Segment 2: Amendment Process
The process to amend the constitution is as follows:

1. A proposed change, where at least `20%` of the national population participates with an approval of at least `50% + 1`.
2. There must not be more than 2 current active changes. If there are more than 2 active changes, a queue will be formed, in the order of highest approval.
3. Active changes must undergo a national compulsory vote, where `75%` of the population must approve.
4. The active change becomes an accepted change and is implemented into the constitution.

#### Segment 3: Genesis Council Amendments
The Genesis Council can enact instant emergency changes to the constitution by Council Vote to protect the sovereignty and stability of the country, but will generally abstain from doing so.

# Part 2: National Profile
### Section 2: Name
#### Segment 1:
The name of this country shall be referred to as `Arkovia`.
```
