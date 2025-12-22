# Power Automate — Insurance Quotation Validation Flow

## 🏦 Business Context (Banking & Insurance)

In many banking channels, insurance quotations are requested from the front-end (web or mobile) with customer and product data.  
These requests often require **multiple validations, business rules, and conditional routing** before a quotation can be generated or sent to an insurance provider.

Without automation, this process leads to:
- Inconsistent validations
- Manual checks by back-office teams
- Delays in customer response times
- Higher operational risk
---

## 💡 Automated Solution

This Power Automate flow validates and orchestrates insurance quotation requests coming from a banking front-end, ensuring that only **valid, complete, and compliant requests** are processed.

The automation acts as a **business gatekeeper** between the front-end and internal/external insurance services.
---

## 🔁 Flow Overview

1. **Trigger**  
   The flow starts when the front-end sends a quotation request (via HTTP or form submission).

2. **Input Validation**  
   Mandatory fields are validated:
   - Customer identification
   - Product type
   - Coverage amount
   - Risk parameters

3. **Business Rules**  
   - Coverage limits validation  
   - Product eligibility checks  
   - Conditional logic based on amount, age, or risk profile

4. **Routing Logic**  
   - Automatic approval for low-risk quotations  
   - Manual or conditional review for higher-risk cases

5. **Integration & Response**  
   - Valid requests are forwarded to the insurance service  
   - Invalid requests return structured error responses to the front-end

6. **Audit & Logging**  
   All requests and outcomes are logged for traceability and compliance.

---

## 🧠 Key Capabilities Demonstrated

- Functional business analysis
- Front-end to backend orchestration
- Data validation & conditional logic
- Error handling & controlled responses
- Enterprise-ready automation design
- Banking & insurance domain understanding

---

<details>
<summary>🇪🇸 Versión en Español</summary>

## 🏦 Contexto del Negocio (Banca y Seguros)

En los canales bancarios, las cotizaciones de seguros se solicitan desde el front-end con datos del cliente y del producto.  
Estas solicitudes requieren múltiples validaciones y reglas de negocio antes de ser procesadas.

Sin automatización, el proceso genera:
- Errores manuales
- Falta de trazabilidad
- Demoras en la respuesta al cliente
- Sobrecarga operativa

---

## 💡 Solución Automatizada

Este flujo en Power Automate valida y orquesta solicitudes de cotización de seguros, asegurando que solo las solicitudes **correctas y completas** continúen el proceso.

El flujo actúa como un **filtro de negocio** entre el front-end y los servicios de seguros.

---

## 🔁 Descripción del Flujo

1. Disparo desde el front-end  
2. Validación de datos obligatorios  
3. Aplicación de reglas de negocio  
4. Enrutamiento condicional  
5. Respuesta controlada al front-end  
6. Registro y auditoría del proceso

---

## 🧠 Capacidades Demostradas

- Análisis funcional
- Validaciones complejas
- Lógica condicional
- Automatización end-to-end
- Diseño orientado a entornos bancarios

</details>
