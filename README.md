# Parking Management System  

## Overview  
A console-based application for managing vehicle parking operations including entry/exit tracking, fee calculation, and parking statistics.  

## Features  

### Core Functionalities  
- Vehicle entry registration  
- Vehicle exit processing with automatic fee calculation  
- Dynamic pricing (50 rupees under 1 hour, 70 rupees over)  
- Real-time parking statistics view  
- Data persistence through file storage  

### Technical Implementation  
- Linked List data structure for vehicle management  
- File handling for data persistence  
- Time tracking for parking duration  

## Usage  

### Menu Options  
1. Vehicle Entry - Register incoming vehicles  
2. Vehicle Exit - Process departing vehicles  
3. Parking Fee - View total collected fees  
4. Parking Statistics - List parked vehicles  
5. Exit - Save data and quit  

## Data Storage  
- Vehicle records saved in `parking_system.txt`  
- Stores registration numbers, driver names, and vehicle details  

## Limitations  
- Basic time calculation  
- No user authentication  
- Console interface only  

## Future Improvements  
- Enhanced time precision  
- User authentication system  
- Graphical interface  
- Database integration  
