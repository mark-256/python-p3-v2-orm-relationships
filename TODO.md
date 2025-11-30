# TODO: Implement One-to-Many Relationship between Department and Employee

- [ ] Update lib/employee.py: Add import for Department class
- [ ] Update lib/employee.py: Modify **init** method to include department_id parameter
- [ ] Update lib/employee.py: Update **repr** method to include Department ID
- [ ] Update lib/employee.py: Update create_table classmethod to add department_id column with foreign key
- [ ] Update lib/employee.py: Update save method to handle department_id
- [ ] Update lib/employee.py: Update update method to handle department_id
- [ ] Update lib/employee.py: Update create classmethod to handle department_id
- [ ] Update lib/employee.py: Update instance_from_db classmethod to handle row[3]
- [ ] Update lib/department.py: Add employees method to return list of associated Employee instances
- [ ] Run pytest -x to verify tests pass
