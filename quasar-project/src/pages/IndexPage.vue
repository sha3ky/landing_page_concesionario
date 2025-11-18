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
              Deja de competir en Wallapop y Autoscout. Ten tu propia plataforma premium donde tú
              eres el protagonista.
            </p>
            <div class="hero-actions">
              <q-btn
                label="Ver Demo en Vivo"
                color="primary"
                size="lg"
                class="cta-button"
                icon="play_arrow"
              />
              <q-btn
                label="Solicitar Presupuesto"
                outline
                color="primary"
                size="lg"
                class="cta-button-outline"
              />
            </div>
          </div>
          <div class="col-12 col-md-6">
            <!--  <div class="hero-image">
              <q-img src="~assets/hero-car.png" alt="Concesionario Profesional" class="hero-img" />
            </div> -->
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

    <!-- Problem vs Solution -->
    <section class="problem-solution-section">
      <div class="container">
        <h2 class="section-title">¿Cansado de Competir en Marketplaces?</h2>
        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-6">
            <div class="problem-card">
              <div class="card-header problem">
                <q-icon name="cancel" class="problem-icon" />
                <h3>Problema: Competir en Wallapop/Autoscout ...</h3>
              </div>
              <ul class="feature-list">
                <li><q-icon name="close" /> Comisiones por cada venta (3-5%)</li>
                <li><q-icon name="close" /> Miles de competidores en la misma página</li>
                <li><q-icon name="close" /> Clientela que solo busca lo más barato</li>
                <li><q-icon name="close" /> No construyes tu marca personal</li>
                <li><q-icon name="close" /> Limitado por reglas de la plataforma</li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="solution-card">
              <div class="card-header solution">
                <q-icon name="check_circle" class="solution-icon" />
                <h3>Solución: Tu Plataforma Profesional</h3>
              </div>
              <ul class="feature-list">
                <li><q-icon name="check" /> Cero comisiones por venta</li>
                <li><q-icon name="check" /> Solo tus coches, sin competencia directa</li>
                <li><q-icon name="check" /> Clientela que valora tu expertise</li>
                <li><q-icon name="check" /> Construyes tu marca profesional</li>
                <li><q-icon name="check" /> Control total sobre tu negocio</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Pricing Comparison -->
    <section class="pricing-section">
      <div class="container">
        <h2 class="section-title">Inversión Clara vs Costes Ocultos</h2>
        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-6">
            <div class="pricing-card marketplace">
              <div class="pricing-header">
                <h3>Marketplaces Genéricos</h3>
                <div class="price">"Gratis"*</div>
              </div>
              <ul class="pricing-features">
                <li><q-icon name="euro" /> €200-500/mes en anuncios destacados</li>
                <li><q-icon name="percent" /> 3-5% comisión por venta</li>
                <li><q-icon name="schedule" /> 5-10 horas/semana en regateos</li>
                <li><q-icon name="visibility_off" /> No construyes valor de marca</li>
                <li><q-icon name="groups" /> Compites con miles</li>
              </ul>
              <div class="pricing-note">*Costes reales ocultos</div>
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="pricing-card professional">
              <div class="pricing-header">
                <h3>Tu Plataforma Profesional</h3>
                <div class="price">€1199 + €100/mes</div>
              </div>
              <ul class="pricing-features">
                <li><q-icon name="check" /> Cero comisiones por venta</li>
                <li><q-icon name="check" /> Clientela cualificada desde día 1</li>
                <li><q-icon name="check" /> Tu marca, tus reglas</li>
                <li><q-icon name="check" /> Control total del negocio</li>
                <li><q-icon name="check" /> Todo incluido</li>
              </ul>
              <q-btn label="Comenzar Ahora" color="primary" size="lg" class="full-width" />
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
          <div class="col-12 col-sm-6 col-md-4" v-for="feature in features" :key="feature.id">
            <div class="feature-card">
              <q-icon :name="feature.icon" class="feature-icon" />
              <h4>{{ feature.title }}</h4>
              <p>{{ feature.description }}</p>
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
            <p>Video demostración de 60 segundos</p>
          </div>
        </div>
        <div class="text-center q-mt-xl">
          <q-btn
            label="Ver Demo Completa"
            color="primary"
            size="xl"
            icon="play_arrow"
            class="cta-button-large"
          />
        </div>
      </div>
    </section>
  </q-page>
</template>

<script setup>
const features = [
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
]
</script>

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

  .hero-image {
    text-align: center;

    .hero-img {
      max-width: 100%;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
    }
  }
}

/* Problem Solution Section */
.problem-solution-section {
  padding: 80px 0;
  background: #f8f9fa;

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

    .card-header {
      display: flex;
      align-items: center;
      margin-bottom: 1.5rem;

      &.problem {
        color: #e74c3c;
      }

      &.solution {
        color: #27ae60;
      }

      .problem-icon,
      .solution-icon {
        font-size: 2rem;
        margin-right: 1rem;
      }

      h3 {
        margin: 0;
        font-size: 1.5rem;
      }
    }
  }

  .feature-list {
    list-style: none;
    padding: 0;

    li {
      display: flex;
      align-items: center;
      margin-bottom: 1rem;
      font-size: 1.1rem;

      .q-icon {
        margin-right: 0.5rem;
        font-size: 1.2rem;
      }
    }
  }
}

/* Pricing Section */
.pricing-section {
  padding: 80px 0;
  background: white;

  .section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #2c3e50;
  }

  .pricing-card {
    background: white;
    border-radius: 15px;
    padding: 2.5rem;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
    height: 100%;
    border: 2px solid transparent;

    &.professional {
      border-color: #3498db;
      position: relative;
      transform: scale(1.05);
    }

    .pricing-header {
      text-align: center;
      margin-bottom: 2rem;

      h3 {
        font-size: 1.5rem;
        margin-bottom: 1rem;
        color: #2c3e50;
      }

      .price {
        font-size: 2.5rem;
        font-weight: 700;
        color: #3498db;
      }
    }

    .pricing-features {
      list-style: none;
      padding: 0;
      margin-bottom: 2rem;

      li {
        display: flex;
        align-items: center;
        margin-bottom: 1rem;
        font-size: 1.1rem;

        .q-icon {
          margin-right: 0.5rem;
          font-size: 1.2rem;
        }
      }
    }

    .pricing-note {
      text-align: center;
      font-style: italic;
      color: #7f8c8d;
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

  .pricing-card.professional {
    transform: none !important;
  }
}
</style>
