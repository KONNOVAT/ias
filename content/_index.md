---
title: 'Главная'
date: 2025-04-25
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Оптимизируй CRM вместе с LLM-INTEGRATION 
      text: 🧱 ПРОСТО. СВОБОДНО. БЕЗ ТРУДНОСТЕЙ 🧱
      primary_action:
        text: Начать
        url: https://konnovat.github.io/ias/#solutions
        icon: rocket-launch
      announcement:
        text: "Новая версия интерфейса на подходе"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
        - statistic: "3k+"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Возможности
      text: Дальше - больше!
      items:
        - name: Оптимизация CRM
          icon: magnifying-glass
          description: Оптимизируйте систему под ваши потребности
        - name: Быстрые решения
          icon: bolt
          description: Быстрое создание софта
        - name: Просто в использовании
          icon: sparkles
          description: Используйте систему без заморочек
        - name: Возможность проф. роста
          icon: code-bracket
          description: Теперь не нужно тратить время на бесполезную рутину
        - name: Высокая продуктивность сотрудников
          icon: star
          description: Ваши сотрудники скажут вам "Спасибо"
        - name: Удобство использования
          icon: rectangle-group
          description: Используйте систему удобно
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Оптимизируйте вашу систему
          text: 1, 2, 3!
          feature_icon: check
          features:
            - "LLM-INTERGTATION - компания будущего для развития CRM систем в сторону AI-оптимизации"
            - "Сохранение вашего бюджета за счет сокращения штата"
            - "Теперь никаких сложностей с сотрудниками!"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Узнать больше
            url: https://konnovat.github.io/ias/#solutions
        - title: Целевая аудитория
          text: 1. Корпоративные клиенты:
                •	Крупные компании: Организации, которые ищут способы автоматизации процессов, улучшения обслуживания клиентов и повышения эффективности работы.
                •	Малый и средний бизнес (МСБ): Компании, которые хотят внедрить современные технологии, но могут иметь ограниченные ресурсы.
                2. Отрасли:
                •	Финансовый сектор: Банки и финансовые учреждения, заинтересованные в автоматизации обработки данных, анализа рисков и улучшении клиентского сервиса.
                •	Здравоохранение: Медицинские учреждения, которые могут использовать LLM для управления записями пациентов и автоматизации взаимодействия с ними.
                •	Образование: Учебные заведения, которые хотят внедрить интеллектуальные системы для поддержки обучения и взаимодействия с учащимися.
                3. Технологические компании:
                •	Стартапы и ИТ-компании: Компании, разрабатывающие программное обеспечение, которые могут интегрировать LLM в свои продукты для улучшения функциональности.
                4. Государственные учреждения:
                •	Организации, работающие в сфере государственного управления, которые ищут способы повышения эффективности и прозрачности своих процессов.
                5. Маркетинговые агентства:
                •	Компании, которые могут использовать LLM для анализа данных, создания контента и улучшения взаимодействия с клиентами.
                6. Индивидуальные пользователи:
                •	Разработчики и технические специалисты, заинтересованные в использовании LLM для создания собственных приложений и решений.
                7. Исследовательские организации:
                •	Университеты и научные учреждения, которые могут использовать LLM для обработки и анализа больших объемов данных в своих исследованиях.

          feature_icon: bolt
          features:
            - "Система блочных структур"
            - "3,000+ пользователей"
            - "Организуй пространство с комфортом"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Мария Иванова"
          role: "Маркетолог компании МАРС-СИСТЕМС"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Моя компания расцвела с приходом в неё LLM-INTEGRATION"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Построй систему мечты вместе с нами!
      text: Просто, как  1, 2, 3!
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
