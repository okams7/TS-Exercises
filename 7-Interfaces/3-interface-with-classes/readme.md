اكتب برنامجًا باستخدام TypeScript يحتوي على واجهة (Interface) وفئة (Class) تقوم بتنفيذ هذه الواجهة باستخدام implements.

### **المتطلبات:**

**قم بتعريف واجهة باسم Employee تحتوي على:**

خاصية name (اسم الموظف) من النوع string.

خاصية age (عمر الموظف) من النوع number.

خاصية position (وظيفة الموظف) من النوع string.

خاصية salary (راتب الموظف) من النوع number.

دالة calculateAnnualSalary() تقوم بحساب الراتب السنوي وتُرجع قيمة من النوع number.

**قم بإنشاء فئة (Class) باسم EmployeeDetails:**

يجب أن تقوم الفئة بـ implements للواجهة Employee.

تحتوي على مُنشئ (constructor) لتعيين القيم للخصائص.

تنفذ الدالة calculateAnnualSalary() بحيث تحسب الراتب السنوي (الراتب الشهري × 12).

قم بإنشاء كائن من الفئة EmployeeDetails يحتوي على معلومات موظف (الاسم، العمر، الوظيفة، والراتب الشهري).

استدعِ دالة calculateAnnualSalary() للكائن لحساب الراتب السنوي، وقم بعرض المعلومات التالية:

اسم الموظف.
الوظيفة.
الراتب الشهري.
الراتب السنوي.