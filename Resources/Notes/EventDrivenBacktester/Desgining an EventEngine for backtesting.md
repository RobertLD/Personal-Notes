## Components 
1. Events\
	- The types of events the system needs to monitor for
	1. 
3. Event Queue
	- A place to store all of the events
4. DataHandler
	- The data handler generates market events from historical data
5. Strategy
	- The Strategy is responsible for taking in market data and generating SignalEvents which will be used to generate a portfolio
6. Portfolio
	- The portfolio's role is to take SignalEvents from the strategy and from those generates order events given the current portfolio
7. ExecutionHandler
	- The execution handler simulates the connection to a broker. The job of the execution handler is to take order-events off the queue and execute them. The execution handler will then generate fill-events
8. EventLoop
	- The event loop is the primary driver of the backtesting engine, forwarding events to the proper components.