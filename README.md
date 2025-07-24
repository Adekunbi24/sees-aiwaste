# Silver Sterlyn Eco Solution Dashboard

## Overview

The Silver Sterlyn Eco Solution Dashboard provides an overview of waste generation and management across Nigeria. This React component visualizes waste data through various statistics and interactive maps, helping users monitor and analyze waste management efforts.

## Features

- **Waste Statistics**: View total waste, recycled waste, critical areas, and waste trends.
- **Interactive Map**: Visualize waste distribution across different locations in Nigeria.
- **AI-Powered Forecasting**: Machine learning predictions based on historical waste data.
- **Customizable Views**: Filter data by state and time period for detailed analysis.

## Components

- **MapContainer**: Displays an interactive map of waste distribution.
- **StatsCard**: Shows key statistics about waste management.
- **AIForecastChart**: Provides AI-powered waste forecasting based on historical data.

## Usage

To use this dashboard in your project, follow these steps:

1. **Install Dependencies**: Ensure you have React and other necessary dependencies installed.

```bash
npm install react lucide-react
```

2. **Import the Dashboard Component**: Include the Dashboard component in your application.

```jsx
import { Dashboard } from './path-to-dashboard/Dashboard';
```

3. **Integrate with Your Data**: Use the `WasteDataContext` to provide waste data to the dashboard.

```jsx
import { WasteDataProvider } from '../context/WasteDataContext';

function App() {
  return (
    <WasteDataProvider>
      <Dashboard />
    </WasteDataProvider>
  );
}
```

4. **Run Your Application**: Start your React application to view the dashboard.

```bash
npm start
````

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
