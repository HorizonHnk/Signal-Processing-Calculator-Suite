# Signal Processing Calculator Suite
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive web application featuring 39 specialized calculators for signal processing, Fourier analysis, circuit analysis, and frequency domain calculations. Built with React and modern UI components.

## 🚀 Features

### Signal Processing Tools
- **Discrete Time Signal Analysis**
  - DT signal computations
  - Unit step sequence analysis
  - Signal decomposition
  - Recursive signal processing

### Fourier Analysis
- **Fourier Series Coefficients**
  - Rectangular waves
  - Triangle waves
  - Trapezoidal waves
- **Transform Analysis**
  - Magnitude spectrum calculation
  - Frequency domain analysis
  - DFT without windowing

### Circuit Analysis
- **RC Circuit Tools**
  - Sinusoidal response
  - Unit step response
  - Ramp response
  - Exponential input analysis
- **RLC & RL Circuits**
  - Transfer function analysis
  - Impulse response calculation
  - Complex circuit behavior

### Advanced Tools
- **Transfer Functions**
  - Unit step input analysis
  - Exponential input processing
- **Z-Transform Analysis**
  - Complex sequence processing
  - System response calculation
- **Visualization**
  - Multi-function signal plotting 
  - Multi-interval visualization
  - Interactive waveform display

## 🛠️ Technical Stack

- **Frontend Framework**: React
- **UI Components**: shadcn/ui
- **Routing**: React Router v6
- **Icons**: Lucide React
- **Styling**: Tailwind CSS
- **Theme**: Dark/Light mode support

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/signal-processing-calculator.git

# Navigate to project directory
cd signal-processing-calculator

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🔧 Required Dependencies

```json
{
  "dependencies": {
    "@radix-ui/react-alert-dialog": "^1.0.0",
    "@radix-ui/react-dropdown-menu": "^2.0.0",
    "@radix-ui/react-slot": "^1.0.0",
    "@radix-ui/react-tabs": "^1.0.0",
    "class-variance-authority": "^0.7.0",
    "clsx": "^2.0.0",
    "lucide-react": "^0.263.1",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.0.0",
    "recharts": "^2.0.0",
    "tailwind-merge": "^2.0.0",
    "tailwindcss": "^3.0.0"
  }
}
```

## 📚 Documentation

The application includes comprehensive documentation for each calculator, accessible via the Documentation page. Each tool includes:

- Detailed description of functionality
- Input parameters and constraints
- Example calculations
- Theoretical background
- Usage guidelines

## 🖥️ Component Structure

```
src/
├── components/
│   ├── calculators/
│   │   ├── ButterworthGainCalculator/
│   │   ├── FourierCalculator/
│   │   └── ... (37 more calculators)
│   ├── layout/
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   └── ThemeToggle.jsx
│   └── ui/
│       ├── button.jsx
│       ├── card.jsx
│       └── ... (more UI components)
├── pages/
│   ├── Home.jsx
│   ├── Documentation.jsx
│   └── SignalCalculator.jsx
└── App.jsx
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name
- Contributors

## 🙏 Acknowledgments

- shadcn/ui for the component library
- Lucide React for the icons
- All contributors and maintainers

## 📧 Contact

- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com
