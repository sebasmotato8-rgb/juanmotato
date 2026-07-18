# Cinora - Case Study

## Mini Proyector HY320 | Ecommerce en Shopify + Custom Liquid Theme

---

## 📋 Executive Summary

**Cinora** es una tienda en línea especializada en la venta del Mini Proyector HY320 en el mercado colombiano. El proyecto demuestra expertise en:

- ✅ Diseño y desarrollo de ecommerce profesional
- ✅ Integración de pagos (PayPal, Mercado Pago)
- ✅ Fulfillment and logistics (Dropi integration)
- ✅ Shopify theme customization con Liquid
- ✅ User experience optimization
- ✅ Legal compliance (términos, privacidad, RGPD)

**Estado:** En operación
**URL:** [cinora.shop](https://cinora.shop)

---

## 🎯 Desafío / Oportunidad

### Mercado
- Mercado colombiano creciente en electrónica y entretenimiento
- Demanda de proyectores portátiles para cine en casa y presentaciones
- Competencia fragmentada, oportunidad de diferenciación

### Objetivo
Crear una tienda en línea profesional que:
1. Venda el Mini Proyector HY320 de forma confiable
2. Proporcione buena experiencia de usuario
3. Maneje pagos de múltiples métodos
4. Integre fulfillment automático
5. Sea escalable y mantenible

---

## 🛠️ Stack Técnico

### Core Ecommerce
- **Plataforma:** Shopify (plan estándar)
- **Lenguaje de templating:** Liquid
- **Base:** Theme personalizado basado en Dawn (Shopify's modern theme)

### Frontend
- **HTML5** con semántica SEO
- **CSS3** con diseño responsivo
- **Vanilla JavaScript** para interactividad

### Pagos
- **PayPal Checkout**
- **Mercado Pago** (primario para Colombia)
- **Conversión de divisas** automática

### Fulfillment
- **Dropi API** para integración de inventario
- Sincronización automática de órdenes
- Stock management en tiempo real

### Performance & SEO
- Optimización de imágenes (WebP, lazy loading)
- Minificación de CSS/JS
- SEO on-page (meta tags, schema.org)
- Mobile-first responsive design

---

## 📐 Arquitectura & Features

### 1. Diseño Visual
**Estética:** Dark/Purple minimalist con tonos corporativos
**Paleta de colores:**
- Primary: `#7C3AED` (Purple - marca Cinora)
- Prefix CSS: `cn-` (Cinora namespace)
- Scheme: Dark mode optimizado

**Responsive:**
- Desktop: Full layout con hero completo
- Tablet: Ajustes de grid y spacing
- Mobile: Single column, CTA flotante

### 2. Estructura de Páginas

#### Home / Landing
- Hero section con hero image del proyector
- Value proposition clara
- Testimonios o reviews
- Call-to-action (comprar)
- FAQ section

#### Product Page
- Galería de imágenes interactiva
- Descripción completa del producto
- Especificaciones técnicas
- Selector de variantes (si aplica)
- Reviews y ratings
- Related products
- Trust badges (seguridad, garantía)

#### Carrito & Checkout
- Carrito drawer personalizado
- Checkout de una página
- Métodos de pago integrados
- Estimación de envío
- Cross-sells en checkout

#### Páginas Legales
- Política de privacidad (RGPD compatible)
- Términos de servicio
- Política de reembolsos
- Términos de envío
- Información de contacto

### 3. Funcionalidades Implementadas

#### E-commerce Core
- Catálogo de productos dinámico
- Sistema de carritos
- Checkout de una página
- Gestión de órdenes
- Notificaciones de pedido

#### Integración Pagos
- PayPal checkout nativo
- Mercado Pago redirect flow
- Manejo de errores de pago
- Confirmación de pago

#### Fulfillment
- Sync automático con Dropi
- Actualización de stock en tiempo real
- Avisos de producto agotado

#### SEO & Performance
- URLs limpias y descriptivas
- Meta tags optimizados
- Optimización de imágenes

---

## 💡 Decisiones Técnicas Clave

### 1. ¿Por qué Shopify?
- **Ventaja:** No requiere mantenimiento de backend
- **Ventaja:** Integración fácil con múltiples payment gateways
- **Ventaja:** Escalabilidad automática
- **Ventaja:** App ecosystem robusto
- **Trade-off:** Menor control sobre arquitectura que custom dev

### 2. ¿Por qué Liquid vs. Temas default?
- **Ventaja:** Control total sobre markup y styles
- **Ventaja:** Capacidad de crear componentes custom
- **Ventaja:** Mejor SEO (control de estructura)
- **Trade-off:** Requiere conocimiento de Liquid

### 3. ¿Por qué Dropi?
- **Ventaja:** Fulfillment automático (no manejo físico)
- **Ventaja:** Integración nativa con Shopify
- **Ventaja:** Precios competitivos en Colombia
- **Ventaja:** Escalable (sin límite de órdenes)

---

## 🔐 Seguridad & Compliance

### Shopify Security
- ✅ PCI compliance out-of-box
- ✅ SSL certificate automático
- ✅ DDoS protection

### Legal
- ✅ Política de privacidad RGPD-compatible
- ✅ Términos de servicio
- ✅ Consentimiento explícito para emails

---

## 🚀 Despliegue & Mantenimiento

### Proceso de Deploy
1. **Local:** Editar theme en VS Code
2. **Staging:** Shopify preview theme
3. **Testing:** QA en staging
4. **Production:** Publish theme
5. **Monitoring:** Shopify dashboard

---

## 🎓 Lecciones Aprendidas

### ✅ Qué funcionó bien
1. **Enfoque al usuario:** UX simple y clara
2. **Múltiples pagos:** No alienar a clientes
3. **Fulfillment automático:** Cero overhead operacional
4. **Mobile-first:** Mayoría del tráfico es mobile

### ⚠️ Retos superados
1. **Integración Mercado Pago:** Requirió debugging cuidadoso
2. **Sincronización Dropi:** Edge cases con stock
3. **Regulación colombiana:** Cumplimiento de leyes locales
4. **Logística:** Coordinar con múltiples couriers

---

## 🔗 Links & Recursos

- **Sitio:** [cinora.shop](https://cinora.shop)
- **Documentación Shopify:** [shopify.dev](https://shopify.dev)
- **Liquid docs:** [shopify.com/docs/liquid](https://shopify.com/docs/liquid)

---

## 📞 Contacto

¿Preguntas sobre este proyecto?

- **Email:** [juan_smotatoa@soy.sena.edu.co](mailto:juan_smotatoa@soy.sena.edu.co)
- **Instagram:** [@juanmotato](https://instagram.com/juanmotato)

---

**Autor:** Juan Sebastián Motato Amariles
**Status:** ✅ En operación
