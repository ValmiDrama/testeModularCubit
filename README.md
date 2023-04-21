# app_lanamone

Projeto com a finalidade de testa o modular e cubit.

Estrutura em features:

```
.                  
├── features                                 # All features or Modules 
│   ├─ auth                                  # Auth's MVC       
│   │  ├── auth_model.dart   
│   │  ├── auth_controller.dart  
│   │  └── auth_page.dart                      
│   ├─ home                                  # Home's MVC       
│   │  ├── home_model.dart   
│   │  ├── home_controller.dart  
│   │  └── home_page.dart                        
│   └─ product                               # Product's MVC     
│      ├── product_model.dart   
│      ├── product_controller.dart
│      └── product_page.dart                    
├── core                                     # Tools and utilities
├── app_widget.dart                          # Main Widget containing MaterialApp 
└── main.dart                                # runApp
```
