rect id
left to right direction
actor User
actor Admin

rectangle "TipidGas System" {
    usecase "Register / Login" as UC1
    usecase "View Fuel Prices" as UC2
    usecase "Search Nearby Gas Stations" as UC3
    usecase "Compare Fuel Prices" as UC4
    usecase "Record Fuel Expenses" as UC5
    usecase "View Expense History" as UC6
    usecase "View Trip History" as UC7
    usecase "View Fuel Efficiency Reports" as UC8
    
    usecase "Update Fuel Prices" as UC9
    usecase "Manage System Data" as UC10
}

User --> UC1
User --> UC2
User --> UC3
User --> UC4
User --> UC5
User --> UC6
User --> UC7
User --> UC8

Admin --> UC9
Admin --> UC10
