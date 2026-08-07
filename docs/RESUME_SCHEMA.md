# Resume JSON Schema

This document defines the standardized JSON structure that the Resume Parser must generate for every uploaded resume.

{
  "name": "",
  "headline": "",
  "email": "",
  "phone": "",
  "location": "",

  "skills": [
    {
      "category": "",
      "name": ""
    }
  ],

  "education": [
    {
      "level": "",
      "degree": "",
      "field_of_study": "",
      "institution": "",
      "start_year": "",
      "end_year": "",
      "grade": {
        "type": "",
        "value": ""
      }
    }
  ],

  "experience": [
    {
      "company": "",
      "positions": [
        {
          "title": "",
          "employment_type": "",
          "location": "",
          "start_date": "",
          "end_date": "",
          "currently_working": false
        }
      ],
      "technologies": [],
      "responsibilities": [],
      "projects": [
        {
          "project_name": "",
          "description": ""
        }
      ]
    }
  ],

  "projects": [
    {
      "project_name": "",
      "description": "",
      "problem_statement": "",
      "role": "",
      "tech_stack": [],
      "features": [],
      "start_date": "",
      "end_date": "",
      "links": [
        {
          "platform": "",
          "url": ""
        }
      ]
    }
  ],

  "certifications": [
    {
      "certificate_name": "",
      "organization": "",
      "issue_date": "",
      "expiry_date": "",
      "credential_id": "",
      "credential_url": ""
    }
  ],

  "links": [
    {
      "platform": "",
      "url": ""
    }
  ]
}
