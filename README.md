actor Patient

rectangle "Appointment System" 
{
    usecase "Book Appointment"
    usecase "View Appointment"
}

Patient --> "Book Appointment"
Patient --> "View Appointment"
