THIS IS A REPOSITORY WITH TASKS FROM THE 3-MONTH SHORT SPECIALIZATION IN ALX-SWE-BACKEND.

CONTENT CONTEXT
===============

1. alx-backend-javascript

=====================

Tasks:

1. Const or let?
	
	Modify:

	function taskFirst to instantiate variables using const

	function taskNext to instantiate variables using let

		export function taskFirst() {
  			var task = 'I prefer const when I can.';
			return task;
		}

		export function getLast() {
	  		return ' is okay';
		}

		export function taskNext() {
			var combination = 'But sometimes let';
			combination += getLast();

			return combination;
		}

