```mermaid
erDiagram
    USER ||--o{ TIME_SLOT : creates
    USER ||--o{ BOOKING : makes
    TIME_SLOT ||--o| BOOKING : has
    USER ||--o{ NOTIFICATION : receives

    USER {
        integer id
        string full_name
        string email
        string phone
        string password_hash
        string role
        string status
    }

    TIME_SLOT {
        integer id
        integer tutor_id
        datetime start_time
        datetime end_time
        string status
    }

    BOOKING {
        integer id
        integer slot_id
        integer student_id
        string status
    }

    NOTIFICATION {
        integer id
        integer user_id
        integer booking_id
        string type
        string status
    }
```
