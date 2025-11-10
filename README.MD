:root {
  /* Primitive Color Tokens */
  --color-white: rgba(255, 255, 255, 1);
  --color-black: rgba(0, 0, 0, 1);
  --color-cream-50: rgba(252, 252, 249, 1);
  --color-cream-100: rgba(255, 255, 253, 1);
  --color-gray-200: rgba(245, 245, 245, 1);
  --color-gray-300: rgba(167, 169, 169, 1);
  --color-gray-400: rgba(119, 124, 124, 1);
  --color-slate-500: rgba(98, 108, 113, 1);
  --color-brown-600: rgba(94, 82, 64, 1);
  --color-charcoal-700: rgba(31, 33, 33, 1);
  --color-charcoal-800: rgba(38, 40, 40, 1);
  --color-slate-900: rgba(19, 52, 59, 1);
  --color-teal-300: rgba(50, 184, 198, 1);
  --color-teal-400: rgba(45, 166, 178, 1);
  --color-teal-500: rgba(33, 128, 141, 1);
  --color-teal-600: rgba(29, 116, 128, 1);
  --color-teal-700: rgba(26, 104, 115, 1);
  --color-teal-800: rgba(41, 150, 161, 1);
  --color-red-400: rgba(255, 84, 89, 1);
  --color-red-500: rgba(192, 21, 47, 1);
  --color-orange-400: rgba(230, 129, 97, 1);
  --color-orange-500: rgba(168, 75, 47, 1);

  --color-brown-600-rgb: 94, 82, 64;
  --color-teal-500-rgb: 33, 128, 141;
  --color-slate-900-rgb: 19, 52, 59;
  --color-slate-500-rgb: 98, 108, 113;
  --color-red-500-rgb: 192, 21, 47;
  --color-red-400-rgb: 255, 84, 89;
  --color-orange-500-rgb: 168, 75, 47;
  --color-orange-400-rgb: 230, 129, 97;

  --color-bg-1: rgba(59, 130, 246, 0.08);
  --color-bg-2: rgba(245, 158, 11, 0.08);
  --color-bg-3: rgba(34, 197, 94, 0.08);
  --color-bg-4: rgba(239, 68, 68, 0.08);
  --color-bg-5: rgba(147, 51, 234, 0.08);
  --color-bg-6: rgba(249, 115, 22, 0.08);
  --color-bg-7: rgba(236, 72, 153, 0.08);
  --color-bg-8: rgba(6, 182, 212, 0.08);

  --color-background: var(--color-cream-50);
  --color-surface: var(--color-cream-100);
  --color-text: var(--color-slate-900);
  --color-text-secondary: var(--color-slate-500);
  --color-primary: var(--color-teal-500);
  --color-primary-hover: var(--color-teal-600);
  --color-primary-active: var(--color-teal-700);
  --color-secondary: rgba(var(--color-brown-600-rgb), 0.12);
  --color-secondary-hover: rgba(var(--color-brown-600-rgb), 0.2);
  --color-secondary-active: rgba(var(--color-brown-600-rgb), 0.25);
  --color-border: rgba(var(--color-brown-600-rgb), 0.2);
  --color-btn-primary-text: var(--color-cream-50);
  --color-card-border: rgba(var(--color-brown-600-rgb), 0.12);
  --color-card-border-inner: rgba(var(--color-brown-600-rgb), 0.12);
  --color-error: var(--color-red-500);
  --color-success: var(--color-teal-500);
  --color-warning: var(--color-orange-500);
  --color-info: var(--color-slate-500);
  --color-focus-ring: rgba(var(--color-teal-500-rgb), 0.4);
  --color-select-caret: rgba(var(--color-slate-900-rgb), 0.8);

  --focus-ring: 0 0 0 3px var(--color-focus-ring);
  --focus-outline: 2px solid var(--color-primary);

  --font-family-base: 'Poppins', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  --font-size-xs: 11px;
  --font-size-sm: 12px;
  --font-size-base: 14px;
  --font-size-md: 14px;
  --font-size-lg: 16px;
  --font-size-xl: 18px;
  --font-size-2xl: 20px;
  --font-size-3xl: 24px;
  --font-size-4xl: 30px;
  --font-weight-normal: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 550;
  --font-weight-bold: 600;
  --line-height-tight: 1.2;
  --line-height-normal: 1.5;
  --letter-spacing-tight: -0.01em;

  --space-0: 0;
  --space-1: 1px;
  --space-2: 2px;
  --space-4: 4px;
  --space-6: 6px;
  --space-8: 8px;
  --space-10: 10px;
  --space-12: 12px;
  --space-16: 16px;
  --space-20: 20px;
  --space-24: 24px;
  --space-32: 32px;

  --radius-sm: 6px;
  --radius-base: 8px;
  --radius-md: 10px;
  --radius-lg: 12px;
  --radius-full: 9999px;

  --shadow-xs: 0 1px 2px rgba(0, 0, 0, 0.02);
  --shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.04), 0 1px 2px rgba(0, 0, 0, 0.02);
  --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.04), 0 2px 4px -1px rgba(0, 0, 0, 0.02);
  --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.04), 0 4px 6px -2px rgba(0, 0, 0, 0.02);
  --shadow-inset-sm: inset 0 1px 0 rgba(255, 255, 255, 0.15), inset 0 -1px 0 rgba(0, 0, 0, 0.03);

  --duration-fast: 150ms;
  --duration-normal: 250ms;
  --ease-standard: cubic-bezier(0.16, 1, 0.3, 1);
}

@media (prefers-color-scheme: dark) {
  :root {
    --color-gray-400-rgb: 119, 124, 124;
    --color-teal-300-rgb: 50, 184, 198;
    --color-gray-300-rgb: 167, 169, 169;
    --color-gray-200-rgb: 245, 245, 245;
    --color-background: var(--color-charcoal-700);
    --color-surface: var(--color-charcoal-800);
    --color-text: var(--color-gray-200);
    --color-text-secondary: rgba(var(--color-gray-300-rgb), 0.7);
    --color-primary: var(--color-teal-300);
    --color-primary-hover: var(--color-teal-400);
    --color-primary-active: var(--color-teal-800);
    --color-secondary: rgba(var(--color-gray-400-rgb), 0.15);
    --color-secondary-hover: rgba(var(--color-gray-400-rgb), 0.25);
    --color-secondary-active: rgba(var(--color-gray-400-rgb), 0.3);
    --color-border: rgba(var(--color-gray-400-rgb), 0.3);
    --color-error: var(--color-red-400);
    --color-success: var(--color-teal-300);
    --color-warning: var(--color-orange-400);
    --color-info: var(--color-gray-300);
    --color-focus-ring: rgba(var(--color-teal-300-rgb), 0.4);
    --color-btn-primary-text: var(--color-slate-900);
    --color-card-border: rgba(var(--color-gray-400-rgb), 0.2);
    --color-card-border-inner: rgba(var(--color-gray-400-rgb), 0.15);
  }
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: var(--font-family-base);
  background: var(--color-background);
  color: var(--color-text);
  line-height: var(--line-height-normal);
  -webkit-font-smoothing: antialiased;
}

/* Landing Page Styles */
.landing-page {
  min-height: 100vh;
}

.hero-section {
  min-height: 100vh;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: var(--space-32);
  position: relative;
  overflow: hidden;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: -50%;
  right: -20%;
  width: 600px;
  height: 600px;
  background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
  border-radius: 50%;
}

.hero-section::after {
  content: '';
  position: absolute;
  bottom: -30%;
  left: -10%;
  width: 500px;
  height: 500px;
  background: radial-gradient(circle, rgba(255,255,255,0.08) 0%, transparent 70%);
  border-radius: 50%;
}

.hero-content {
  text-align: center;
  max-width: 900px;
  z-index: 1;
  animation: fadeInUp 1s ease-out;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.hero-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: linear-gradient(135deg, #ff6b6b 0%, #4ecdc4 100%);
  margin: 0 auto var(--space-32);
  box-shadow: 0 20px 60px rgba(0,0,0,0.3);
  animation: pulse 3s ease-in-out infinite;
}

@keyframes pulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
}

.hero-content h1 {
  font-size: 56px;
  font-weight: 700;
  margin-bottom: var(--space-20);
  line-height: 1.1;
}

.hero-content .subtitle {
  font-size: 24px;
  margin-bottom: var(--space-32);
  opacity: 0.95;
  font-weight: 500;
}

.cta-buttons {
  display: flex;
  gap: var(--space-16);
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  padding: 16px 32px;
  border-radius: 50px;
  font-size: 16px;
  font-weight: 600;
  border: none;
  cursor: pointer;
  transition: all 0.3s ease;
  text-decoration: none;
  display: inline-block;
}

.btn-primary {
  background: white;
  color: #667eea;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

.btn-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 15px 40px rgba(0,0,0,0.3);
}

.btn-secondary {
  background: transparent;
  color: white;
  border: 2px solid white;
}

.btn-secondary:hover {
  background: rgba(255,255,255,0.1);
  transform: translateY(-3px);
}

.features-section {
  padding: 80px var(--space-32);
  background: var(--color-surface);
}

.features-grid {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: var(--space-32);
}

.feature-card {
  text-align: center;
  padding: var(--space-32);
  background: var(--color-background);
  border-radius: var(--radius-lg);
  border: 1px solid var(--color-card-border);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow-lg);
}

.feature-icon {
  width: 60px;
  height: 60px;
  margin: 0 auto var(--space-16);
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 28px;
}

.feature-card h3 {
  margin-bottom: var(--space-12);
  font-size: var(--font-size-xl);
}

.feature-card p {
  color: var(--color-text-secondary);
  line-height: 1.6;
}

.testimonials-section {
  padding: 80px var(--space-32);
  background: var(--color-bg-5);
}

.section-header {
  text-align: center;
  max-width: 700px;
  margin: 0 auto var(--space-32);
}

.section-header h2 {
  font-size: 42px;
  margin-bottom: var(--space-16);
}

.section-header p {
  font-size: var(--font-size-lg);
  color: var(--color-text-secondary);
}

.testimonials-grid {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: var(--space-24);
}

.testimonial-card {
  background: var(--color-surface);
  padding: var(--space-32);
  border-radius: var(--radius-lg);
  border: 1px solid var(--color-card-border);
  box-shadow: var(--shadow-sm);
}

.testimonial-header {
  display: flex;
  align-items: center;
  gap: var(--space-16);
  margin-bottom: var(--space-16);
}

.testimonial-avatar {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background: linear-gradient(135deg, #ff6b6b 0%, #4ecdc4 100%);
}

.testimonial-info h4 {
  margin-bottom: var(--space-4);
}

.testimonial-info p {
  color: var(--color-text-secondary);
  font-size: var(--font-size-sm);
}

.testimonial-text {
  line-height: 1.7;
  color: var(--color-text-secondary);
}

.stats-section {
  padding: 60px var(--space-32);
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
}

.stats-grid {
  max-width: 900px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: var(--space-32);
}

.stat-item h3 {
  font-size: 48px;
  margin-bottom: var(--space-8);
}

.stat-item p {
  font-size: var(--font-size-lg);
  opacity: 0.9;
}

/* Main App Styles */
.main-app {
  display: none;
  min-height: 100vh;
}

.main-app.active {
  display: block;
}

.app-header {
  background: var(--color-surface);
  border-bottom: 1px solid var(--color-border);
  padding: var(--space-16) var(--space-32);
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 100;
}

.app-logo {
  font-size: var(--font-size-xl);
  font-weight: 700;
  color: var(--color-primary);
}

.tab-navigation {
  background: var(--color-surface);
  border-bottom: 2px solid var(--color-border);
  padding: 0 var(--space-32);
  display: flex;
  gap: var(--space-8);
  overflow-x: auto;
}

.tab-btn {
  padding: var(--space-16) var(--space-24);
  background: none;
  border: none;
  border-bottom: 3px solid transparent;
  color: var(--color-text-secondary);
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s ease;
  white-space: nowrap;
  font-size: var(--font-size-base);
}

.tab-btn:hover {
  color: var(--color-text);
  background: var(--color-secondary);
}

.tab-btn.active {
  color: var(--color-primary);
  border-bottom-color: var(--color-primary);
}

.tab-content {
  display: none;
  padding: var(--space-32);
  max-width: 1400px;
  margin: 0 auto;
}

.tab-content.active {
  display: block;
  animation: fadeIn 0.3s ease;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

/* Templates Tab */
.template-filters {
  margin-bottom: var(--space-32);
  display: flex;
  gap: var(--space-16);
  flex-wrap: wrap;
  align-items: center;
}

.filter-select {
  padding: var(--space-10) var(--space-16);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-base);
  background: var(--color-surface);
  color: var(--color-text);
  font-size: var(--font-size-base);
  cursor: pointer;
}

.templates-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: var(--space-24);
}

.template-card {
  background: var(--color-surface);
  border: 1px solid var(--color-card-border);
  border-radius: var(--radius-lg);
  overflow: hidden;
  transition: all 0.3s ease;
  cursor: pointer;
}

.template-card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow-lg);
}

.template-preview {
  height: 200px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 48px;
  position: relative;
}

.template-card-body {
  padding: var(--space-20);
}

.template-header {
  display: flex;
  justify-content: space-between;
  align-items: start;
  margin-bottom: var(--space-12);
}

.template-card h3 {
  font-size: var(--font-size-lg);
  margin-bottom: var(--space-4);
}

.template-badge {
  display: inline-block;
  padding: var(--space-4) var(--space-10);
  background: var(--color-secondary);
  border-radius: var(--radius-full);
  font-size: var(--font-size-xs);
  font-weight: 500;
  color: var(--color-text);
}

.favorite-btn {
  background: none;
  border: none;
  font-size: 20px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

.favorite-btn:hover {
  transform: scale(1.2);
}

.favorite-btn.active {
  color: #ffd700;
}

.template-description {
  color: var(--color-text-secondary);
  margin-bottom: var(--space-16);
  font-size: var(--font-size-sm);
}

.color-scheme-preview {
  display: flex;
  gap: var(--space-6);
  margin-bottom: var(--space-16);
}

.color-dot {
  width: 24px;
  height: 24px;
  border-radius: 50%;
  border: 2px solid var(--color-border);
}

.template-actions {
  display: flex;
  gap: var(--space-8);
}

.btn-small {
  flex: 1;
  padding: var(--space-8) var(--space-16);
  border-radius: var(--radius-base);
  border: none;
  font-size: var(--font-size-sm);
  font-weight: 500;
  cursor: pointer;
  transition: all 0.2s ease;
}

.btn-outline {
  background: transparent;
  border: 1px solid var(--color-border);
  color: var(--color-text);
}

.btn-outline:hover {
  background: var(--color-secondary);
}

.btn-primary-small {
  background: var(--color-primary);
  color: var(--color-btn-primary-text);
}

.btn-primary-small:hover {
  background: var(--color-primary-hover);
}

/* Personal Info Tab */
.form-section {
  max-width: 800px;
  margin: 0 auto;
}

.form-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: var(--space-24);
}

.form-group {
  margin-bottom: var(--space-24);
}

.form-label {
  display: block;
  margin-bottom: var(--space-8);
  font-weight: 500;
  color: var(--color-text);
}

.required {
  color: var(--color-error);
}

.form-input {
  width: 100%;
  padding: var(--space-12);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-base);
  background: var(--color-surface);
  color: var(--color-text);
  font-size: var(--font-size-base);
  font-family: inherit;
  transition: border-color 0.2s ease;
}

.form-input:focus {
  outline: none;
  border-color: var(--color-primary);
  box-shadow: var(--focus-ring);
}

textarea.form-input {
  min-height: 120px;
  resize: vertical;
}

.profile-upload {
  display: flex;
  align-items: center;
  gap: var(--space-24);
  padding: var(--space-24);
  background: var(--color-bg-1);
  border-radius: var(--radius-lg);
}

.profile-preview {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 48px;
}

.upload-info p {
  margin-bottom: var(--space-8);
  color: var(--color-text-secondary);
}

/* Sections Tab */
.sections-list {
  max-width: 800px;
  margin: 0 auto;
}

.section-item {
  display: flex;
  align-items: center;
  gap: var(--space-16);
  padding: var(--space-20);
  background: var(--color-surface);
  border: 1px solid var(--color-card-border);
  border-radius: var(--radius-lg);
  margin-bottom: var(--space-16);
  cursor: move;
}

.drag-handle {
  font-size: 20px;
  color: var(--color-text-secondary);
  cursor: grab;
}

.section-info {
  flex: 1;
}

.section-info h3 {
  margin-bottom: var(--space-4);
  font-size: var(--font-size-lg);
}

.section-info p {
  color: var(--color-text-secondary);
  font-size: var(--font-size-sm);
}

.toggle-switch {
  position: relative;
  width: 50px;
  height: 26px;
}

.toggle-input {
  opacity: 0;
  width: 0;
  height: 0;
}

.toggle-slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: var(--color-secondary);
  transition: 0.3s;
  border-radius: 26px;
}

.toggle-slider:before {
  position: absolute;
  content: "";
  height: 20px;
  width: 20px;
  left: 3px;
  bottom: 3px;
  background-color: white;
  transition: 0.3s;
  border-radius: 50%;
}

.toggle-input:checked + .toggle-slider {
  background-color: var(--color-primary);
}

.toggle-input:checked + .toggle-slider:before {
  transform: translateX(24px);
}

/* Design Tab */
.design-panel {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: var(--space-32);
}

.design-section {
  background: var(--color-surface);
  padding: var(--space-24);
  border-radius: var(--radius-lg);
  border: 1px solid var(--color-card-border);
}

.design-section h3 {
  margin-bottom: var(--space-20);
  font-size: var(--font-size-xl);
}

.color-schemes-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
  gap: var(--space-12);
}

.color-scheme-card {
  padding: var(--space-12);
  border: 2px solid var(--color-border);
  border-radius: var(--radius-base);
  cursor: pointer;
  transition: all 0.2s ease;
}

.color-scheme-card:hover {
  border-color: var(--color-primary);
  transform: scale(1.05);
}

.color-scheme-card.active {
  border-color: var(--color-primary);
  background: var(--color-bg-1);
}

.color-scheme-colors {
  display: flex;
  gap: var(--space-4);
  margin-bottom: var(--space-8);
}

.color-scheme-dot {
  width: 30px;
  height: 30px;
  border-radius: 50%;
}

.color-scheme-name {
  font-size: var(--font-size-sm);
  font-weight: 500;
  text-align: center;
}

.color-picker-group {
  display: flex;
  gap: var(--space-16);
}

.color-picker-item {
  flex: 1;
}

.color-picker {
  width: 100%;
  height: 50px;
  border: 1px solid var(--color-border);
  border-radius: var(--radius-base);
  cursor: pointer;
}

.font-select {
  width: 100%;
  padding: var(--space-12);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-base);
  background: var(--color-background);
  color: var(--color-text);
  font-size: var(--font-size-base);
  margin-bottom: var(--space-16);
}

.size-controls {
  display: flex;
  gap: var(--space-8);
}

.size-btn {
  flex: 1;
  padding: var(--space-10);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-base);
  background: var(--color-surface);
  cursor: pointer;
  transition: all 0.2s ease;
}

.size-btn:hover {
  background: var(--color-secondary);
}

.size-btn.active {
  background: var(--color-primary);
  color: var(--color-btn-primary-text);
  border-color: var(--color-primary);
}

/* Preview Tab */
.preview-container {
  background: var(--color-surface);
  border-radius: var(--radius-lg);
  overflow: hidden;
}

.preview-toolbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: var(--space-16);
  background: var(--color-background);
  border-bottom: 1px solid var(--color-border);
}

.device-selector {
  display: flex;
  gap: var(--space-8);
}

.device-btn {
  padding: var(--space-8) var(--space-16);
  border: 1px solid var(--color-border);
  background: var(--color-surface);
  border-radius: var(--radius-base);
  cursor: pointer;
  transition: all 0.2s ease;
}

.device-btn:hover {
  background: var(--color-secondary);
}

.device-btn.active {
  background: var(--color-primary);
  color: var(--color-btn-primary-text);
  border-color: var(--color-primary);
}

.preview-frame {
  margin: var(--space-24) auto;
  background: white;
  border-radius: var(--radius-base);
  box-shadow: var(--shadow-lg);
  overflow: auto;
  max-height: 800px;
  transition: all 0.3s ease;
}

.preview-frame.mobile {
  max-width: 375px;
}

.preview-frame.tablet {
  max-width: 768px;
}

.preview-frame.desktop {
  max-width: 100%;
}

/* Export Tab */
.export-options {
  max-width: 800px;
  margin: 0 auto;
}

.export-format-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: var(--space-24);
  margin-bottom: var(--space-32);
}

.export-card {
  padding: var(--space-24);
  background: var(--color-surface);
  border: 2px solid var(--color-card-border);
  border-radius: var(--radius-lg);
  cursor: pointer;
  transition: all 0.3s ease;
  text-align: center;
}

.export-card:hover {
  border-color: var(--color-primary);
  transform: translateY(-3px);
  box-shadow: var(--shadow-md);
}

.export-card.selected {
  border-color: var(--color-primary);
  background: var(--color-bg-1);
}

.export-icon {
  font-size: 48px;
  margin-bottom: var(--space-16);
}

.export-card h3 {
  margin-bottom: var(--space-8);
}

.export-card p {
  color: var(--color-text-secondary);
  font-size: var(--font-size-sm);
}

.export-settings {
  background: var(--color-surface);
  padding: var(--space-24);
  border-radius: var(--radius-lg);
  border: 1px solid var(--color-card-border);
  margin-bottom: var(--space-32);
}

.checkbox-group {
  display: flex;
  align-items: center;
  gap: var(--space-8);
  margin-bottom: var(--space-16);
}

.checkbox-group input[type="checkbox"] {
  width: 20px;
  height: 20px;
  cursor: pointer;
}

.export-action {
  text-align: center;
}

.btn-export {
  padding: var(--space-16) var(--space-32);
  background: var(--color-primary);
  color: var(--color-btn-primary-text);
  border: none;
  border-radius: var(--radius-base);
  font-size: var(--font-size-lg);
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn-export:hover {
  background: var(--color-primary-hover);
  transform: translateY(-2px);
  box-shadow: var(--shadow-md);
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 36px;
  }
  
  .hero-content .subtitle {
    font-size: 18px;
  }
  
  .cta-buttons {
    flex-direction: column;
    width: 100%;
  }
  
  .btn {
    width: 100%;
  }
  
  .design-panel {
    grid-template-columns: 1fr;
  }
  
  .tab-navigation {
    padding: 0 var(--space-16);
  }
  
  .tab-btn {
    padding: var(--space-12) var(--space-16);
    font-size: var(--font-size-sm);
  }
  
  .templates-grid {
    grid-template-columns: 1fr;
  }
}

.hidden {
  display: none !important;
}