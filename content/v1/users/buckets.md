---
title: Users - Buckets | Dribbble API
---

# Buckets

* TOC
{:toc}

## List buckets for a user

List a user's buckets:

    GET /users/:user/buckets

List the authenticated user's buckets:

    GET /user/buckets

### Response

<%= headers 200 %>
<%= json(:bucket) { |hash| [hash] } %>