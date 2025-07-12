# Entry_Queue_Manager

This project simulates a smart **Entry Queue Management System** for stadiums with multiple entry gates. The primary objective is to **minimize the total time** taken for all attendees to enter the stadium by providing **real-time queue suggestions**.

## Features

- Supports **N entry gates**, each maintaining its own queue.
- Each attendee takes a fixed **`p` minutes** to enter through a gate.
- System starts with a **random initial assignment** of `M/2` people (half of the total attendees) distributed across the queues.
- Attendees are allowed to **switch queues anytime** to reduce their wait.
- The system provides real-time guidance on:
  - **Waiting time** at each gate (calculated as queue length × `p`)
  - **Recommended gate(s)** to switch to for the shortest expected wait

## Objective

To **optimize the entry flow** by reducing wait times through intelligent queue management, helping M attendees enter the stadium as quickly and efficiently as possible.

## Applications

- Large-scale public venues: stadiums, concerts, exhibitions, festivals
- Any event with multiple entry points and high footfall

This project showcases an approach to **smart crowd control** using simple queueing logic and adaptive recommendations to improve attendee experience and reduce congestion.
