<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ing. Software - Sistema Gestión Veterinaria</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <style>
        :root {
            --primary-color: #1a2a6c;
            --secondary-color: #2a3f7c;
            --accent-color: #4caf50;
            --light-color: #e8eaf6;
        }
        
        body {
            background-color: #f8f9fa;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .navbar-custom {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
        }
        
        .hero-section {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 100px 0;
        }
        
        .profile-img {
            width: 200px;
            height: 200px;
            border: 5px solid white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .service-card {
            border: none;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            overflow: hidden;
            height: 100%;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        
        .service-popular {
            border: 3px solid var(--accent-color);
            position: relative;
        }
        
        .popular-badge {
            position: absolute;
            top: -10px;
            right: 20px;
            background: var(--accent-color);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
        }
        
        .price-amount {
            font-size: 2.5rem;
            font-weight: bold;
            margin: 20px 0;
        }
        
        .price-period {
            color: rgba(255,255,255,0.8);
            font-size: 1rem;
        }
        
        .feature-list {
            list-style: none;
            padding: 0;
            margin: 30px 0;
        }
        
        .feature-list li {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }
        
        .feature-list li:last-child {
            border-bottom: none;
        }
        
        .feature-list li i {
            color: var(--accent-color);
            margin-right: 10px;
        }
        
        .btn-primary-custom {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            border: none;
            border-radius: 10px;
            padding: 12px 30px;
            font-weight: 600;
            transition: all 0.3s;
            color: white;
        }
        
        .btn-primary-custom:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(26, 42, 108, 0.3);
        }
        
        .tech-stack {
            background: white;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .tech-icon {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: var(--primary-color);
        }
        
        .benefit-card {
            background: white;
            border-radius: 12px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            height: 100%;
            transition: transform 0.3s;
        }
        
        .benefit-card:hover {
            transform: translateY(-5px);
        }
        
        .benefit-icon {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }
        
        .process-step {
            text-align: center;
            padding: 30px;
        }
        
        .step-number {
            width: 60px;
            height: 60px;
            background: var(--primary-color);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: bold;
            margin: 0 auto 20px;
        }
        
        .contact-card {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 15px;
            padding: 40px;
        }
        
        .certification-badge {
            background: var(--accent-color);
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            font-size: 0.9rem;
            display: inline-block;
            margin: 5px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark navbar-custom fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">
                <i class="bi bi-code-slash me-2"></i>Ing. Software Freelance 
            </a>
            <div class="navbar-nav ms-auto">
                <a class="nav-link" href="https://wa.me/525654255366" target="_blank">
                    <i class="bi bi-whatsapp me-1"></i>WhatsApp
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-8">
                    <h1 class="display-4 fw-bold mb-4">Desarrollo de Software </h1>
                    <p class="lead mb-4">Ingeniero de Software Freelance - Soluciones personalizadas y eficientes</p>
                    <div class="d-flex flex-wrap gap-2 mb-4">
                        <span class="certification-badge">PHP/MySQL</span>
                        <span class="certification-badge">JavaScript</span>
                        <span class="certification-badge">Bootstrap 5</span>
                        <span class="certification-badge">Desarrollo Full-Stack</span>
                    </div>
                    <a href="https://wa.me/525654255366" class="btn btn-light btn-lg">
                        <i class="bi bi-calendar-check me-2"></i>Solicitar Cotización
                    </a>
                </div>
                <div class="col-md-4 text-center">
                    <img src="perfil2.png" alt="Ingeniero de Software" class="profile-img rounded-circle">
                    <h4 class="mt-3">Jose Luis Rodriguez</h4>
                    <p class="text-light">Ingeniero de Software</p>
                    <div class="text-warning">
                        <i class="bi bi-star-fill"></i>
                        <i class="bi bi-star-fill"></i>
                        <i class="bi bi-star-fill"></i>
                        <i class="bi bi-star-fill"></i>
                        
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-5 mt-5">
        <div class="container">
            <h2 class="section-title">Servicios de Desarrollo</h2>
            <p class="text-center mb-5">Soluciones completas para automatizar y optimizar tu negocios</p>
            
            <div class="row g-4">
                <!-- Servicio Básico -->
                <div class="col-md-4">
                    <div class="service-card h-100">
                        <div class="service-header">
                            <h4>Plan Básico</h4>
                            <div class="price-amount">$14,000</div>
                            <div class="price-period">Pago único • 1-2 semanas</div>
                        </div>
                        <div class="card-body p-4">
                            <ul class="feature-list">
                                <li><i class="bi bi-check-circle"></i> Sistema de agendamiento básico</li>
                                <li><i class="bi bi-check-circle"></i> Panel administrativo simple</li>
                                <li><i class="bi bi-check-circle"></i> Gestión de clientes y productos</li>
                                <li><i class="bi bi-check-circle"></i> Diseño responsive</li>
                                <li><i class="bi bi-check-circle"></i> Base de datos MySQL</li>
                                <li><i class="bi bi-clock"></i> <strong>Entrega: 1-2 semanas</strong></li>
                                <li><i class="bi bi-headset"></i> Soporte técnico: 30 días</li>
                            </ul>
                            <div class="text-center">
                                <a href="https://wa.me/525654255366?text=Me interesa el Plan Básico de $14,000 MXN" 
                                   class="btn btn-outline-primary w-100" target="_blank">
                                    <i class="bi bi-whatsapp me-2"></i>Solicitar
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Servicio Estándar (Recomendado) -->
                <div class="col-md-4">
                    <div class="service-card h-100 service-popular">
                        <div class="popular-badge">MÁS SOLICITADO</div>
                        <div class="service-header">
                            <h4>Plan Estándar</h4>
                            <div class="price-amount">$31,000</div>
                            <div class="price-period">Pago único • 3-4 semanas</div>
                        </div>
                        <div class="card-body p-4">
                            <ul class="feature-list">
                                <li><i class="bi bi-check-circle"></i> <strong>Sistema completo de gestión</strong></li>
                                <li><i class="bi bi-check-circle"></i> Roles: Cliente y Administrador</li>
                                <li><i class="bi bi-check-circle"></i> Reprogramación y cancelación</li>
                                <li><i class="bi bi-check-circle"></i> Historial médico completo</li>
                                <li><i class="bi bi-check-circle"></i> Validación de horarios</li>
                                <li><i class="bi bi-check-circle"></i> Control de días festivos</li>
                                <li><i class="bi bi-clock"></i> <strong>Entrega: 3-4 semanas</strong></li>
                                <li><i class="bi bi-headset"></i> <strong>Soporte: 60 días incluido</strong></li>
                            </ul>
                            <div class="text-center">
                                <a href="https://wa.me/525654255366?text=Me interesa el Plan Estándar de $31,000 MXN" 
                                   class="btn btn-primary-custom w-100" target="_blank">
                                    <i class="bi bi-whatsapp me-2"></i>Cotizar Ahora
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Servicio Premium -->
                <div class="col-md-4">
                    <div class="service-card h-100">
                        <div class="service-header">
                            <h4>Plan Premium</h4>
                            <div class="price-amount">$52,000</div>
                            <div class="price-period">Pago único • 5-6 semanas</div>
                        </div>
                        <div class="card-body p-4">
                            <ul class="feature-list">
                                <li><i class="bi bi-check-circle"></i> Todo el plan Estándar +</li>
                                <li><i class="bi bi-check-circle"></i> Recordatorios automáticos</li>
                                <li><i class="bi bi-check-circle"></i> Integración WhatsApp/Email</li>
                                <li><i class="bi bi-check-circle"></i> App móvil básica</li>
                                <li><i class="bi bi-check-circle"></i> Reportes avanzados</li>
                                <li><i class="bi bi-check-circle"></i> Dashboard analítico</li>
                                <li><i class="bi bi-clock"></i> <strong>Entrega: 5-6 semanas</strong></li>
                                <li><i class="bi bi-headset"></i> Soporte: 90 días incluido</li>
                            </ul>
                            <div class="text-center">
                                <a href="https://wa.me/525654255366?text=Me interesa el Plan Premium de $52,000 MXN" 
                                   class="btn btn-outline-primary w-100" target="_blank">
                                    <i class="bi bi-whatsapp me-2"></i>Solicitar
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ROI Section -->
    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Inversión Inteligente con ROI Garantizado</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="benefit-card">
                        <div class="benefit-icon">
                            <i class="bi bi-clock"></i>
                        </div>
                        <h5>Ahorro de Tiempo</h5>
                        <p>Automatización de procesos administrativos</p>
                        <h4 class="text-success">$5,000 - $7,000 MXN/mes</h4>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="benefit-card">
                        <div class="benefit-icon">
                            <i class="bi bi-calendar-x"></i>
                        </div>
                        <h5>Optimización de Citas</h5>
                        <p>Reducción de citas perdidas y mejor organización</p>
                        <h4 class="text-success">$3,500 - $8,600 MXN/mes</h4>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="benefit-card">
                        <div class="benefit-icon">
                            <i class="bi bi-graph-up"></i>
                        </div>
                        <h5>Eficiencia Operativa</h5>
                        <p>Mejora en la gestión y atención al cliente</p>
                        <h4 class="text-success">$2,600 - $4,300 MXN/mes</h4>
                    </div>
                </div>
            </div>
            <div class="text-center mt-5">
                <div class="alert alert-success d-inline-block">
                    <h4 class="mb-2">ROI Total Estimado: $11,100 - $19,900 MXN/mes</h4>
                    <p class="mb-0 fw-bold">¡Tu inversión se recupera en 2-4 meses!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Tech Stack -->
    <section class="py-5">
        <div class="container">
            <h2 class="section-title">Tecnologías y Metodología</h2>
            <div class="tech-stack">
                <div class="row text-center">
                    <div class="col-md-3 mb-4">
                        <i class="bi bi-filetype-php tech-icon"></i>
                        <h5>PHP 8.x</h5>
                        <p class="text-muted">Backend robusto y seguro</p>
                    </div>
                    <div class="col-md-3 mb-4">
                        <i class="bi bi-database tech-icon"></i>
                        <h5>MySQL</h5>
                        <p class="text-muted">Base de datos relacional</p>
                    </div>
                    <div class="col-md-3 mb-4">
                        <i class="bi bi-bootstrap tech-icon"></i>
                        <h5>Bootstrap 5</h5>
                        <p class="text-muted">Diseño responsive</p>
                    </div>
                    <div class="col-md-3 mb-4">
                        <i class="bi bi-javascript tech-icon"></i>
                        <h5>JavaScript</h5>
                        <p class="text-muted">Interactividad y validaciones</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Development Process -->
    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Proceso de Desarrollo</h2>
            <div class="row">
                <div class="col-md-4 process-step">
                    <div class="step-number">1</div>
                    <h5>Análisis y Planificación</h5>
                    <p>Reunión inicial para entender tus necesidades y planificar el proyecto</p>
                </div>
                <div class="col-md-4 process-step">
                    <div class="step-number">2</div>
                    <h5>Desarrollo Iterativo</h5>
                    <p>Desarrollo por módulos con revisiones constantes y feedback</p>
                </div>
                <div class="col-md-4 process-step">
                    <div class="step-number">3</div>
                    <h5>Entrega y Soporte</h5>
                    <p>Implementación, capacitación y soporte post-entrega</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Payment Plans -->
    <section class="py-5">
        <div class="container">
            <h2 class="section-title">Planes de Pago Flexibles</h2>
            <div class="row g-4 justify-content-center">
                <div class="col-md-4">
                    <div class="text-center p-4 border rounded h-100">
                        <h4>Plan 50/50</h4>
                        <div class="price-amount text-primary">$31,000</div>
                        <p><strong>50% inicial:</strong> $15,500<br><strong>50% final:</strong> $15,500</p>
                        <small class="text-success fw-bold">Recomendado para proyectos estándar</small>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="text-center p-4 border rounded h-100">
                        <h4>Plan 40/30/30</h4>
                        <div class="price-amount text-primary">$31,000</div>
                        <p><strong>40% inicial:</strong> $12,400<br><strong>30% avance:</strong> $9,300<br><strong>30% final:</strong> $9,300</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="text-center p-4 border rounded h-100">
                        <h4>Personalizado</h4>
                        <div class="price-amount text-primary">Consultar</div>
                        <p>Planes a 3-6 meses sin intereses<br>Pregunta por nuestras opciones</p>
                        <small class="text-muted">Sujeto a evaluación</small>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-5 bg-light">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-md-10">
                    <div class="contact-card">
                        <div class="row align-items-center">
                            <div class="col-md-8">
                                <h3 class="mb-3">¿Listo para transformar tu negocio?</h3>
                                <p class="lead mb-4">Agenda una consulta gratuita para analizar tus necesidades</p>
                                <div class="d-flex flex-wrap gap-3">
                                    <a href="https://wa.me/5654255366" class="btn btn-light btn-lg" target="_blank">
                                        <i class="bi bi-whatsapp me-2"></i>WhatsApp
                                    </a>
                                    <a href="mailto:rodriguezeliceriojoseluis@gmail.com" class="btn btn-outline-light btn-lg">
                                        <i class="bi bi-envelope me-2"></i>Email
                                    </a>
                                    <a href="tel:+525654255366" class="btn btn-outline-light btn-lg">
                                        <i class="bi bi-telephone me-2"></i>Llamar
                                    </a>
                                </div>
                            </div>
                            <div class="col-md-4 text-center">
                                <i class="bi bi-chat-quote" style="font-size: 4rem; opacity: 0.8;"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="section-title">Preguntas Frecuentes</h2>
            <div class="row justify-content-center">
                <div class="col-md-10">
                    <div class="accordion" id="faqAccordion">
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#faq1">
                                    ¿Qué garantías ofrecen?
                                </button>
                            </h2>
                            <div id="faq1" class="accordion-collapse collapse show">
                                <div class="accordion-body">
                                    60 días de garantía por bugs y errores críticos. Soporte técnico incluido durante el periodo de garantía.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2">
                                    ¿Incluyen hosting y dominio?
                                </button>
                            </h2>
                            <div id="faq2" class="accordion-collapse collapse">
                                <div class="accordion-body">
                                    No incluidos en el precio base. Puedo ayudarte a configurar hosting (aprox. $2,100-3,100 MXN/año) y dominio ($200-260 MXN/año).
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq3">
                                    ¿Ofrecen mantenimiento posterior?
                                </button>
                            </h2>
                            <div id="faq3" class="accordion-collapse collapse">
                                <div class="accordion-body">
                                    Sí, ofrezco planes de mantenimiento desde $860 MXN/mes para actualizaciones, backups y soporte continuo.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p class="mb-2">&copy; 2024 Ingeniero de Software Freelance Jose Luis Rodriguez Elicerio. Todos los derechos reservados.</p>
            <p class="text-muted mb-0">Especialista en desarrollo de software</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
