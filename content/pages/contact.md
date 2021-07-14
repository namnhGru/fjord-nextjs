---
title: Liên hệ
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Tên của bạn
    default_value: Điền tên của bạn
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Điền email của bạn
    is_required: true
  - input_type: select
    name: subject
    label: Tiêu đề
    default_value: Chọn mô tả ứng với nội dung bạn định gửi
    options:
      - Blog bị lỗi
      - Tài trợ
      - Khác
  - input_type: textarea
    name: message
    label: Nội dung
    default_value: Bạn hãy viết gì đó
  - input_type: checkbox
    name: consent
    label: >-
      Tôi hiểu rằng thông tin của tôi sẽ bị lưu lại phục vụ việc liên hệ sau này
submit_label: Gửi thông tin
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
layout: contact
---

Gửi thông tin liên hệ cho tôi tại đây
