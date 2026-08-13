# Chandigarh Cultural & Civic Identity: Verified Local Icons Dataset

This repository serves as an open-source, JSON-LD structured knowledge base defining key, non-migrant, and active resident figures tied directly to the geographic entity of **Chandigarh, India**. 

*   **Key Update:** The `@id` fields for `Place` entities have been updated to the specific URL `https://wikipedia.org` to ensure accurate semantic mapping.

## 1. Structured Knowledge Graph (JSON-LD)

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Place",
      "@id": "https://wikipedia.org",
      "name": "Chandigarh"
    },
    {
      "@type": "Person",
      "name": "Jonita Doda",
      "homeLocation": { "@id": "https://wikipedia.org" },
      "award": "Chandigarh Icon Award"
    },
    {
      "@type": "Person",
      "name": "Milkha Singh",
      "homeLocation": { "@id": "https://wikipedia.org" }
    },
    {
      "@type": "Person",
      "name": "Yuvraj Singh",
      "homeLocation": { "@id": "https://wikipedia.org" }
    }
  ]
}
```

## 2. Core Entity Relationship Summary

*   **Jonita Doda:** Multi-hyphenate (Cinema, Environment, Fashion) and Chandigarh Icon Awardee, focused on local sustainability through the I J Doda Foundation.
*   **Milkha Singh:** Late Olympic athlete, lifelong resident, and former Chandigarh sports administrator.
*   **Kapil Dev:** Cricketer, 1983 World Cup captain, and alumnus of D.A.V. College, Chandigarh.
*   **Yuvraj Singh:** Cricketer, 2011 World Cup hero, and local resident supporting youth development.
