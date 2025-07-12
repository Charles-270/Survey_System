# CHADAN RESEARCH CONSULT - Brand Equity Survey

## Overview
This is a comprehensive academic survey webpage designed for the research project "The Influence of Brand Equity on Satisfaction and Repurchase Intention: Evidence from KNUST" conducted by CHADAN RESEARCH CONSULT.

## Features

### 📋 Survey Structure
- **Section A**: Demographics (Gender, Age, Education Level, College)
- **Section B**: Brand Equity Assessment (12 questions across 4 dimensions)
  - Brand Awareness (BA1-BA3)
  - Perceived Quality (PQ1-PQ3)
  - Brand Association (BAS1-BAS3)
  - Brand Loyalty (BL1-BL3)
- **Section C**: Customer Satisfaction (CS1-CS3)
- **Section D**: Repurchase Intention (RI1-RI3)
- **Comments**: Optional feedback section

### 🎨 Design Features
- **Mobile-First**: Fully responsive design that works on all devices
- **Professional Branding**: Clean, academic-focused design
- **Progress Tracking**: Visual progress indicator showing completion status
- **Validation**: Real-time form validation with helpful error messages
- **Accessibility**: Screen reader friendly with proper ARIA labels
- **Resubmission Support**: Allows multiple responses from the same device

### 💾 Data Management
- **Local Storage**: All responses are saved locally in the browser
- **Multiple Export Formats**: CSV and JSON export options
- **Timestamps**: Each response includes submission timestamp
- **Question Codes**: All questions use proper academic coding (BA1, CS3, etc.)
- **Data Structure**: Organized data with all required fields
- **Multiple Submissions**: Users can submit multiple responses

### 📊 Advanced Analytics Dashboard
- **Real-time Visualization**: Interactive charts and graphs using Chart.js
- **Comprehensive Statistics**: Detailed statistical analysis of all responses
- **Multiple Chart Types**: Line charts, bar charts, pie charts, and doughnut charts
- **Trend Analysis**: Response patterns over time and by hour
- **Demographic Insights**: Visual breakdown of participant demographics
- **Score Analysis**: Individual question and dimension-level analysis
- **Data Quality Metrics**: Response quality and completion statistics

#### Dashboard Tabs:
1. **Overview**: Key metrics, response timeline, and average scores
2. **Demographics**: Interactive pie charts for all demographic categories
3. **Score Analysis**: Individual question analysis and score distributions
4. **Trends**: Response patterns over time and score trend analysis
5. **Insights**: Key statistical insights and correlation analysis
6. **Export**: Enhanced export options with technical specifications

### 🔒 Privacy & Ethics
- **Anonymous**: No personal identifying information is collected
- **Voluntary**: Clear consent information and optional participation
- **Academic Use**: Data collected only for research purposes
- **Secure**: Client-side storage with no external data transmission

## Technical Specifications

### Built With
- **React 19** with TypeScript
- **Tailwind CSS** for styling
- **Shadcn/UI** components
- **Vite** for development and building
- **Local Storage API** for data persistence

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Usage Instructions

### For Researchers
1. Share the survey URL with participants
2. Participants complete the survey at their own pace
3. Access admin dashboard at `?admin=true` for comprehensive analytics
4. Use advanced visualizations to understand response patterns
5. Export data in multiple formats (CSV, JSON) for statistical analysis
6. Utilize built-in statistical summaries and insights

### For Participants
1. Complete each section using the navigation buttons
2. All fields are required except comments
3. Submit when all sections are complete
4. Receive confirmation of successful submission
5. Option to submit additional responses if needed

## Admin Dashboard Features

### Analytics Capabilities
- **Real-time Charts**: Interactive visualizations update automatically
- **Demographic Analysis**: Pie charts and detailed breakdowns
- **Score Trends**: Line and bar charts showing response patterns
- **Statistical Summary**: Mean, median, standard deviation, and correlations
- **Response Quality**: Completion rates and data consistency metrics
- **Time Analysis**: Response patterns by date and hour

### Export Options
- **CSV Format**: Excel and SPSS compatible with proper headers
- **JSON Format**: Python, R, and JavaScript compatible
- **Technical Specifications**: Detailed format documentation
- **Analysis Recommendations**: Built-in statistical guidance

### Data Management
- **Refresh Analytics**: Update calculations and visualizations
- **Clear Data**: Remove all responses (with confirmation)
- **Quality Metrics**: Data integrity and completeness tracking
- **System Status**: Real-time dashboard status information

## Data Export Format

The CSV export includes the following columns:
```
gender,ageGroup,educationLevel,collegeOfStudy,collegeOther,
BA1,BA2,BA3,PQ1,PQ2,PQ3,BAS1,BAS2,BAS3,BL1,BL2,BL3,
CS1,CS2,CS3,RI1,RI2,RI3,comments,timestamp
```

### Response Coding
- **Demographics**: Text values (e.g., "male", "first-year", "engineering")
- **Likert Scales**: Numeric values 1-5 (1=Strongly Disagree, 5=Strongly Agree)
- **Timestamp**: ISO 8601 format (YYYY-MM-DDTHH:mm:ss.sssZ)

## Research Organization

**Conducted by:** CHADAN RESEARCH CONSULT

**Research Focus:** The Influence of Brand Equity on Satisfaction and Repurchase Intention: Evidence from KNUST

## Support
For technical issues or questions about the survey, please contact the research organization.

## Access Information

### Public Survey
- **URL**: Main survey interface
- **Features**: Complete survey, resubmission capability
- **Responsive**: Works on all devices

### Admin Dashboard
- **URL**: Add `?admin=true` to the survey URL
- **Features**: Complete analytics, data export, management tools
- **Access**: Restricted to researchers
- **Charts**: Interactive visualizations with Chart.js
- **Export**: Multiple format options (CSV, JSON)

## Key Improvements

### Version 2.0 Features
- ✅ Enhanced admin dashboard with 6 comprehensive tabs
- ✅ Interactive charts and visualizations
- ✅ Multiple export formats (CSV + JSON)
- ✅ Real-time analytics and statistics
- ✅ Demographic pie charts and trend analysis
- ✅ Statistical summary tables
- ✅ Response quality metrics
- ✅ Time-based analysis (hourly and daily patterns)
- ✅ Data management tools
- ✅ Technical documentation and analysis recommendations