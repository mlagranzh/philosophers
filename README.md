# philosophers

This project is a training to multi-threads programming with the use of mutex.
It contains program simulating a twist of the famous Dining Philosophers problem.
This project is also a good lesson in C optimization as we need to save every bit of CPU usage we can to ensure the survival of our philosophers.

![philo](https://camo.githubusercontent.com/db61cc08cc9be57152afb22ae99eedde38120c5a2eee648ce28c4345a599ae32/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f372f37622f416e5f696c6c757374726174696f6e5f6f665f7468655f64696e696e675f7068696c6f736f70686572735f70726f626c656d2e706e67){ width: 500px; }
## 💻 DONE

• The philosophers must never be starving. 
• Every philosopher needs to eat. 
• Philosophers don’t speak with each other. 
• Philosophers don’t know when another philosopher is about to die. 
• Each time a philosopher has finished eating, he will drop his forks and start sleeping. 
• When a philosopher is done sleeping, he will start thinking. 
• The simulation stops when a philosopher dies. 
• One fork between each philosopher, therefore if they are multiple philosophers, there will be a fork at the right and the left of each philosopher. 
• Each philosopher should be a thread.

## 📦 Installation
  ```shell
  git clone https://github.com/mlagranzh/philosophers
  ```
 
## 🚀 Run
  ```shell
  make; ./philo number_of_philo time_to_die time_to_eat time_to_sleep
  ```
  
- number_of_philo: is the number of philosophers and also the number of forks.
- time_to_die: is time each philosopher must ate
- time_to_eat: is the time it takes for a philosopher to eat.
- time_to_sleep: is the time the philosopher will spend sleeping.

or run:
  ```shell
  make; ./philo number_of_philo time_to_die time_to_eat time_to_sleep number_of_times
  ```
where  number_of_times is the number each philosopher should eat and then simulation stops.

## 📖 Wiki
- ### [philo_problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem)
