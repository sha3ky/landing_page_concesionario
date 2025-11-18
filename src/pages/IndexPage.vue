<template>
  <q-page class="landing-page">
    <!-- Hero Section -->
    <section class="hero-section">
      <div class="container">
        <div class="row items-center q-col-gutter-xl">
          <div class="col-12 col-md-6">
            <h1 class="hero-title">
              Tu Concesionario Online
              <span class="highlight">Profesional</span>
            </h1>
            <p class="hero-subtitle">
              Deja de competir en Wallapop y Autoscout. Ten tu propia plataforma
              premium donde tú eres el protagonista.
            </p>

            <div class="text-center q-mt-xl">
              <q-btn
                label="Ver Demo en Vivo"
                color="primary"
                size="xl"
                class="cta-button-large"
                icon="open_in_new"
                href="https://jtcars.netlify.app/#/home"
                target="_blank"
              />
            </div>
          </div>
          <div class="col-12 col-md-6">
            <q-img
              src="https://images.unsplash.com/photo-1592198084033-aade902d1aae?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80"
              alt="Concesionario Profesional"
              class="hero-img"
              style="border-radius: 10px"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Nuevo Pricing Tiers Section -->
    <!--    <section class="pricing-tiers-section">
      <div class="container">
        <h2 class="section-title">Elige Tu Plan Perfecto</h2>
        <p class="section-subtitle">Plataforma completa adaptada a tu crecimiento</p>

        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-4">
            <div class="pricing-tier-card">
              <div class="tier-header">
                <div class="tier-badge entrada">🎪 ENTRADA</div>
                <h3>Perfecto para Empezar</h3>
                <div class="price">
                  <span class="amount">€1,199</span>
                  <span class="period">+ €99/mes</span>
                </div>
              </div>
              <ul class="tier-features">
                <li><q-icon name="check" /> Portal web profesional</li>
                <li><q-icon name="check" /> Panel administración básico</li>
                <li><q-icon name="check" /> Hasta 25 vehículos</li>
                <li><q-icon name="check" /> Soporte técnico estándar</li>
                <li><q-icon name="check" /> Hosting incluido</li>
                <li><q-icon name="check" /> Actualizaciones de seguridad</li>
              </ul>
              <q-btn
                label="Comenzar Ahora"
                color="primary"
                size="lg"
                class="full-width tier-btn"
                outline
              />
            </div>
          </div>

          <div class="col-12 col-md-4">
            <div class="pricing-tier-card premium">
              <div class="tier-header">
                <div class="tier-badge premium">🚀 PREMIUM</div>
                <h3>Más Popular</h3>
                <div class="price">
                  <span class="amount">€1,999</span>
                  <span class="period">+ €149/mes</span>
                </div>
              </div>
              <ul class="tier-features">
                <li><q-icon name="check" /> Todo en Entrada +</li>
                <li><q-icon name="check" /> Personalización avanzada</li>
                <li><q-icon name="check" /> Hasta 100 vehículos</li>
                <li><q-icon name="check" /> Soporte prioritario</li>
                <li><q-icon name="check" /> IA para descripciones</li>
                <li><q-icon name="check" /> Analytics integrado</li>
                <li><q-icon name="check" /> Backup diario</li>
              </ul>
              <q-btn label="Elegir Premium" color="primary" size="lg" class="full-width tier-btn" />
              <div class="popular-badge">MÁS ELEGIDO</div>
            </div>
          </div>

          <div class="col-12 col-md-4">
            <div class="pricing-tier-card">
              <div class="tier-header">
                <div class="tier-badge enterprise">🏆 ENTERPRISE</div>
                <h3>Para Grandes Concesionarios</h3>
                <div class="price">
                  <span class="amount">€2,999</span>
                  <span class="period">+ €199/mes</span>
                </div>
              </div>
              <ul class="tier-features">
                <li><q-icon name="check" /> Todo en Premium +</li>
                <li><q-icon name="check" /> Vehículos ilimitados</li>
                <li><q-icon name="check" /> CRM integrado</li>
                <li><q-icon name="check" /> Soporte 24/7</li>
                <li><q-icon name="check" /> Múltiples usuarios admin</li>
                <li><q-icon name="check" /> API personalizada</li>
                <li><q-icon name="check" /> Migración de datos</li>
              </ul>
              <q-btn
                label="Contactar Ventas"
                color="primary"
                size="lg"
                class="full-width tier-btn"
                outline
              />
            </div>
          </div>
        </div>

        <div class="pricing-footer">
          <div class="guarantee-badge">
            <q-icon name="verified" />
            <span>30 días de garantía de satisfacción</span>
          </div>
        </div>
      </div>
    </section> -->

    <!-- Problem vs Solution -->
    <section class="problem-solution-section">
      <div class="container">
        <h2 class="section-title">
          ¿Cansado de Perder Tiempo y Dinero en Wallapop?
        </h2>
        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-6">
            <div class="problem-card">
              <div class="card-header problem">
                <q-icon name="schedule" class="problem-icon" />
                <h3>Problema Real: Marketplaces Genéricos</h3>
              </div>
              <ul class="feature-list q-pa-none q-gutter-y-md">
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>10+ horas/semana&nbsp;</strong> perdidas en
                    mensajes sin sentido</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>95% de contactos no cualificados&nbsp;</strong> -
                    solo "mirones"</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>€200-800/mes en anuncios&nbsp;</strong> para ser
                    visible</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>Cero construcción de marca&nbsp;</strong> - eres un
                    anuncio más</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>Carrera hacia el precio más bajo</strong>, no hacia
                    la calidad</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="close" />
                  <span class="text-subtitle1"
                    ><strong>Imposible fidelizar&nbsp;</strong> clientes
                    satisfechos</span
                  >
                </li>
              </ul>
              <div class="problem-footer">
                <q-icon name="warning" />
                <strong>Coste real oculto: €1,500-3,000/mes</strong>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="solution-card">
              <div class="card-header solution">
                <q-icon name="rocket_launch" class="solution-icon" />
                <h3>Solución: Tu Plataforma Profesional</h3>
              </div>
              <ul class="feature-list q-pa-none q-gutter-y-md">
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>Clientes cualificados&nbsp;</strong> que buscan
                    profesionalidad</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>+80% menos tiempo&nbsp;</strong>gestionando
                    consultas</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>Construyes tu marca&nbsp; </strong> y
                    reputación</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>Cero comisiones&nbsp;</strong> por venta</span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>Vendes valor, no precio</strong></span
                  >
                </li>
                <li class="q-py-sm">
                  <q-icon name="check" />
                  <span class="text-subtitle1"
                    ><strong>Clientes recurrentes&nbsp;</strong> que confían en
                    ti</span
                  >
                </li>
              </ul>
              <div class="solution-footer">
                <q-icon name="savings" />
                <strong>Inversión clara: €1199 + €99/mes</strong>
              </div>
            </div>
          </div>
        </div>

        <div class="pain-questions">
          <h3>💡 Reflexiona:</h3>
          <div class="questions-grid">
            <div class="question-item">
              <q-icon name="schedule" />
              <span
                >¿Cuánto vale 1 hora de tu tiempo respondiendo "¿Me lo dejas más
                barato?"</span
              >
            </div>
            <div class="question-item">
              <q-icon name="groups" />
              <span
                >¿Qué prefieres: 100 contactos de "mirones" o 5 clientes
                serios?</span
              >
            </div>
            <div class="question-item">
              <q-icon name="business" />
              <span
                >¿Estás construyendo el valor de Wallapop o el de TU
                negocio?</span
              >
            </div>
            <div class="question-item">
              <q-icon name="trending_up" />
              <span
                >¿Cuántas ventas pierdes por no tener presencia profesional
                online?</span
              >
            </div>
            <div class="question-item">
              <q-icon name="euro" />
              <span
                >¿€200-800/mes en anuncios o desde €99/mes en tu
                plataforma?</span
              >
            </div>
            <div class="question-item">
              <q-icon name="psychology" />
              <span
                >¿Sigues compitiendo por precio o quieres destacar por calidad y
                servicio?</span
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Features -->
    <section class="features-section">
      <div class="container">
        <h2 class="section-title">Todo Incluido en tu Inversión</h2>
        <div class="row q-col-gutter-lg">
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="design_services" class="feature-icon" />
              <h4>Diseño Web Premium</h4>
              <p>
                Diseño responsive y profesional que convierte visitantes en
                clientes
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="admin_panel_settings" class="feature-icon" />
              <h4>Panel de Administración</h4>
              <p>Gestiona tu inventario y contactos fácilmente</p>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="photo_library" class="feature-icon" />
              <h4>Galería Profesional</h4>
              <p>Muestra tus coches con fotos de alta calidad</p>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="support_agent" class="feature-icon" />
              <h4>Soporte Prioritario</h4>
              <p>Ayuda técnica cuando la necesites</p>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="security" class="feature-icon" />
              <h4>Seguridad y Backup</h4>
              <p>Tus datos protegidos con backup diario</p>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-4">
            <div class="feature-card">
              <q-icon name="update" class="feature-icon" />
              <h4>Actualizaciones Incluidas</h4>
              <p>Mantenemos tu plataforma siempre actualizada</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Video Demo -->
    <section class="video-section">
      <div class="container">
        <h2 class="section-title">Mira Nuestra Plataforma en Acción</h2>
        <div class="video-container">
          <div class="video-placeholder">
            <q-icon name="play_circle" class="play-icon" />
            <p>Video demostración</p>
          </div>
        </div>
        <div class="text-center q-mt-xl">
          <q-btn
            label="Ver Demo en Vivo"
            color="primary"
            size="xl"
            class="cta-button-large"
            icon="open_in_new"
            href="https://jtcars.netlify.app/#/home"
            target="_blank"
          />
        </div>
      </div>
    </section>
  </q-page>
</template>

<style scoped lang="scss">
.landing-page {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Hero Section */
.hero-section {
  padding: 100px 0;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;

  .hero-title {
    font-size: 3.5rem;
    font-weight: 700;
    line-height: 1.1;
    margin-bottom: 1.5rem;

    .highlight {
      background: linear-gradient(45deg, #ffd700, #ffa500);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  }

  .hero-subtitle {
    font-size: 1.3rem;
    opacity: 0.9;
    margin-bottom: 2.5rem;
    line-height: 1.6;
  }

  .hero-actions {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
  }

  .cta-button {
    background: linear-gradient(45deg, #ff6b6b, #ff8e53);
    border: none;
  }
}

/* Nuevo Pricing Tiers Section */
.pricing-tiers-section {
  padding: 80px 0;
  background: #f8f9fa;

  .section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #2c3e50;
  }

  .section-subtitle {
    text-align: center;
    font-size: 1.2rem;
    color: #7f8c8d;
    margin-bottom: 3rem;
  }

  .pricing-tier-card {
    background: white;
    border-radius: 20px;
    padding: 2.5rem;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    height: 100%;
    position: relative;
    transition: transform 0.3s ease;
    border: 2px solid #e9ecef;

    &:hover {
      transform: translateY(-5px);
    }

    &.premium {
      border-color: #3498db;
      transform: scale(1.05);

      &:hover {
        transform: scale(1.05) translateY(-5px);
      }
    }

    .tier-header {
      text-align: center;
      margin-bottom: 2rem;
      padding-bottom: 2rem;
      border-bottom: 2px solid #f8f9fa;

      .tier-badge {
        display: inline-block;
        padding: 0.5rem 1rem;
        border-radius: 25px;
        font-weight: 700;
        font-size: 0.9rem;
        margin-bottom: 1rem;

        &.entrada {
          background: linear-gradient(45deg, #ffd700, #ffa500);
          color: black;
        }

        &.premium {
          background: linear-gradient(45deg, #3498db, #2980b9);
          color: white;
        }

        &.enterprise {
          background: linear-gradient(45deg, #9b59b6, #8e44ad);
          color: white;
        }
      }

      h3 {
        font-size: 1.5rem;
        margin-bottom: 1.5rem;
        color: #2c3e50;
      }

      .price {
        .amount {
          font-size: 3rem;
          font-weight: 700;
          color: #3498db;
          display: block;
        }

        .period {
          font-size: 1.1rem;
          color: #7f8c8d;
        }
      }
    }

    .tier-features {
      list-style: none;
      padding: 0;
      margin-bottom: 2rem;

      li {
        display: flex;
        align-items: center;
        margin-bottom: 1rem;
        font-size: 1rem;
        color: #2c3e50;

        .q-icon {
          color: #27ae60;
          margin-right: 0.8rem;
          font-size: 1.2rem;
        }
      }
    }

    .tier-btn {
      margin-top: auto;
    }

    .popular-badge {
      position: absolute;
      top: -10px;
      right: 20px;
      background: #e74c3c;
      color: white;
      padding: 0.5rem 1rem;
      border-radius: 15px;
      font-size: 0.8rem;
      font-weight: 700;
    }
  }

  .pricing-footer {
    text-align: center;
    margin-top: 3rem;

    .guarantee-badge {
      display: inline-flex;
      align-items: center;
      background: #e8f8f5;
      color: #27ae60;
      padding: 1rem 2rem;
      border-radius: 25px;
      font-weight: 500;

      .q-icon {
        margin-right: 0.5rem;
        font-size: 1.5rem;
      }
    }
  }
}

/* Problem Solution Section */
.problem-solution-section {
  padding: 80px 0;
  background: white;

  .section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #2c3e50;
  }

  .problem-card,
  .solution-card {
    background: white;
    border-radius: 15px;
    padding: 2rem;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    height: 100%;
    position: relative;

    .card-header {
      display: flex;
      align-items: center;
      margin-bottom: 1.5rem;
      padding-bottom: 1rem;
      border-bottom: 2px solid;

      &.problem {
        color: #e74c3c;
        border-bottom-color: #e74c3c;
      }

      &.solution {
        color: #27ae60;
        border-bottom-color: #27ae60;
      }

      .problem-icon,
      .solution-icon {
        font-size: 2rem;
        margin-right: 1rem;
      }

      h3 {
        margin: 0;
        font-size: 1.5rem;
        font-weight: 600;
      }
    }
  }

  .feature-list {
    list-style: none;
    padding: 0;
    margin-bottom: 1.5rem;

    li {
      display: flex;
      align-items: flex-start;
      margin-bottom: 1rem;
      font-size: 1.1rem;
      line-height: 1.4;

      .q-icon {
        margin-right: 0.5rem;
        font-size: 1.2rem;
        margin-top: 0.2rem;
        flex-shrink: 0;
      }

      strong {
        color: #2c3e50;
      }
    }
  }

  .problem-footer,
  .solution-footer {
    padding: 1rem;
    border-radius: 10px;
    display: flex;
    align-items: center;
    font-size: 1.1rem;

    .q-icon {
      margin-right: 0.5rem;
      font-size: 1.3rem;
    }
  }

  .problem-footer {
    background: #ffeaea;
    color: #c0392b;
    border: 1px solid #f5b7b1;
  }

  .solution-footer {
    background: #e8f8f5;
    color: #27ae60;
    border: 1px solid #a3e4d7;
  }

  .pain-questions {
    margin-top: 4rem;
    padding: 2rem;
    background: white;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);

    h3 {
      text-align: center;
      font-size: 1.8rem;
      margin-bottom: 2rem;
      color: #2c3e50;
    }

    .questions-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }

    .question-item {
      display: flex;
      align-items: flex-start;
      padding: 1.5rem;
      background: #f8f9fa;
      border-radius: 10px;
      border-left: 4px solid #3498db;

      .q-icon {
        color: #3498db;
        margin-right: 1rem;
        font-size: 1.5rem;
        margin-top: 0.2rem;
        flex-shrink: 0;
      }

      span {
        font-size: 1.1rem;
        line-height: 1.4;
        color: #2c3e50;
      }
    }
  }
}

/* Features Section */
.features-section {
  padding: 80px 0;
  background: #f8f9fa;

  .section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #2c3e50;
  }

  .feature-card {
    background: white;
    border-radius: 15px;
    padding: 2rem;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    height: 100%;
    transition: transform 0.3s ease;

    &:hover {
      transform: translateY(-5px);
    }

    .feature-icon {
      font-size: 3rem;
      color: #3498db;
      margin-bottom: 1rem;
    }

    h4 {
      font-size: 1.3rem;
      margin-bottom: 1rem;
      color: #2c3e50;
    }

    p {
      color: #7f8c8d;
      line-height: 1.6;
    }
  }
}

/* Video Section */
.video-section {
  padding: 80px 0;
  background: white;

  .section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #2c3e50;
  }

  .video-container {
    max-width: 800px;
    margin: 0 auto;
  }

  .video-placeholder {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    border-radius: 15px;
    padding: 80px 20px;
    text-align: center;
    color: white;
    cursor: pointer;
    transition: transform 0.3s ease;

    &:hover {
      transform: scale(1.02);
    }

    .play-icon {
      font-size: 4rem;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.2rem;
      margin: 0;
    }
  }

  .cta-button-large {
    background: linear-gradient(45deg, #ff6b6b, #ff8e53);
    border: none;
    padding: 1rem 2rem;
  }
}

/* Responsive */
@media (max-width: 768px) {
  .hero-title {
    font-size: 2.5rem !important;
  }

  .hero-actions {
    justify-content: center;
  }

  .pricing-tier-card.premium {
    transform: none !important;

    &:hover {
      transform: translateY(-5px) !important;
    }
  }

  .questions-grid {
    grid-template-columns: 1fr !important;
  }

  .question-item {
    flex-direction: column;
    text-align: center;

    .q-icon {
      margin-right: 0 !important;
      margin-bottom: 0.5rem;
    }
  }

  .popular-badge {
    position: relative !important;
    top: auto !important;
    right: auto !important;
    margin-bottom: 1rem;
  }
}
</style>

<script setup>
/* const features = [
  {
    id: 1,
    icon: 'design_services',
    title: 'Diseño Web Premium',
    description: 'Diseño responsive y profesional que convierte visitantes en clientes',
  },
  {
    id: 2,
    icon: 'admin_panel_settings',
    title: 'Panel de Administración',
    description: 'Gestiona tu inventario y contactos fácilmente',
  },
  {
    id: 3,
    icon: 'photo_library',
    title: 'Galería Profesional',
    description: 'Muestra tus coches con fotos de alta calidad',
  },
  {
    id: 4,
    icon: 'support_agent',
    title: 'Soporte Prioritario',
    description: 'Ayuda técnica cuando la necesites',
  },
  {
    id: 5,
    icon: 'security',
    title: 'Seguridad y Backup',
    description: 'Tus datos protegidos con backup diario',
  },
  {
    id: 6,
    icon: 'update',
    title: 'Actualizaciones Incluidas',
    description: 'Mantenemos tu plataforma siempre actualizada',
  },
] */
</script>
