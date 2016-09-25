# University

class Lectures: 
first_name = None 
last_name = None 
campus = None 
birthday = None 
course = None 
salery = None 
subject = None 

  def _init_ (self, first_name, last_name, campus, birthday, course, salery, subject): 
	self.first_name = first_name 
	self.last_name = last_name 
	self.campus = campus 
	self.birthday = birthday 
	self.course = course 
	self.salery = salery 
	self.subject = subject 

lct1 = Lectures("Jack","Daniels", "3", "01/06/81","CS/2/1, "DS/1/2", "Lector", "Math")

lct2 = Lectures("Mary","Collins", "2", "09/26/76","PE/2/1, "CS/3/2", "Lector", "English")
