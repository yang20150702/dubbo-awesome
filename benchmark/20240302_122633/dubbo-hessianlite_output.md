# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
Iteration   1: 5.645 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.645 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 13.408 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.408 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ops/ms
Iteration   1: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.704 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.049 ops/ms
Iteration   1: 3.869 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.869 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ±(99.9%) 0.112 ms/op
Iteration   1: 2.941 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.278 ±(99.9%) 0.029 ms/op
Iteration   1: 2.086 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.067 ms/op
Iteration   1: 3.079 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.694 ±(99.9%) 0.241 ms/op
Iteration   1: 7.598 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ±(99.9%) 0.126 ms/op
Iteration   1: 3.183 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.928 ms/op
                 createUser·p0.999:  40.221 ms/op
                 createUser·p0.9999: 43.316 ms/op
                 createUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10038
  mean =      3.183 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9854 
    [ 5.000, 10.000) = 120 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.928 ms/op
     p(99.9000) =     40.221 ms/op
     p(99.9900) =     43.316 ms/op
     p(99.9990) =     43.319 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ±(99.9%) 0.090 ms/op
Iteration   1: 1.609 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   1.524 ms/op
                 existUser·p0.90:   2.071 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.025 ms/op
                 existUser·p0.999:  5.745 ms/op
                 existUser·p0.9999: 6.472 ms/op
                 existUser·p1.00:   6.496 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19854
  mean =      1.609 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 358 
    [1.000, 1.500) = 8701 
    [1.500, 2.000) = 8291 
    [2.000, 2.500) = 2009 
    [2.500, 3.000) = 293 
    [3.000, 3.500) = 55 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 24 
    [4.500, 5.000) = 14 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 33 
    [6.000, 6.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      1.524 ms/op
     p(90.0000) =      2.071 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.025 ms/op
     p(99.9000) =      5.745 ms/op
     p(99.9900) =      6.472 ms/op
     p(99.9990) =      6.496 ms/op
     p(99.9999) =      6.496 ms/op
    p(100.0000) =      6.496 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.103 ms/op
Iteration   1: 2.815 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.707 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.892 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 21.362 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11359
  mean =      2.815 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4168 
    [ 2.500,  5.000) = 7081 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.892 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     21.362 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.101 ±(99.9%) 0.449 ms/op
Iteration   1: 8.423 ±(99.9%) 0.156 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   7.946 ms/op
                 listUser·p0.90:   11.649 ms/op
                 listUser·p0.95:   13.189 ms/op
                 listUser·p0.99:   19.398 ms/op
                 listUser·p0.999:  25.834 ms/op
                 listUser·p0.9999: 27.722 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3800
  mean =      8.423 ±(99.9%) 0.156 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 233 
    [ 5.000,  7.500) = 1368 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      7.946 ms/op
     p(90.0000) =     11.649 ms/op
     p(95.0000) =     13.189 ms/op
     p(99.0000) =     19.398 ms/op
     p(99.9000) =     25.834 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.645          ops/ms
Client.existUser                       thrpt         13.408          ops/ms
Client.getUser                         thrpt          9.704          ops/ms
Client.listUser                        thrpt          3.869          ops/ms
Client.createUser                       avgt          2.941           ms/op
Client.existUser                        avgt          2.086           ms/op
Client.getUser                          avgt          3.079           ms/op
Client.listUser                         avgt          7.598           ms/op
Client.createUser                     sample  10038   3.183 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample          1.511           ms/op
Client.createUser:createUser·p0.50    sample          2.953           ms/op
Client.createUser:createUser·p0.90    sample          3.695           ms/op
Client.createUser:createUser·p0.95    sample          4.219           ms/op
Client.createUser:createUser·p0.99    sample          5.928           ms/op
Client.createUser:createUser·p0.999   sample         40.221           ms/op
Client.createUser:createUser·p0.9999  sample         43.316           ms/op
Client.createUser:createUser·p1.00    sample         43.319           ms/op
Client.existUser                      sample  19854   1.609 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.444           ms/op
Client.existUser:existUser·p0.50      sample          1.524           ms/op
Client.existUser:existUser·p0.90      sample          2.071           ms/op
Client.existUser:existUser·p0.95      sample          2.286           ms/op
Client.existUser:existUser·p0.99      sample          3.025           ms/op
Client.existUser:existUser·p0.999     sample          5.745           ms/op
Client.existUser:existUser·p0.9999    sample          6.472           ms/op
Client.existUser:existUser·p1.00      sample          6.496           ms/op
Client.getUser                        sample  11359   2.815 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.817           ms/op
Client.getUser:getUser·p0.50          sample          2.707           ms/op
Client.getUser:getUser·p0.90          sample          3.498           ms/op
Client.getUser:getUser·p0.95          sample          3.727           ms/op
Client.getUser:getUser·p0.99          sample          4.892           ms/op
Client.getUser:getUser·p0.999         sample         20.972           ms/op
Client.getUser:getUser·p0.9999        sample         21.362           ms/op
Client.getUser:getUser·p1.00          sample         21.398           ms/op
Client.listUser                       sample   3800   8.423 ± 0.156   ms/op
Client.listUser:listUser·p0.00        sample          1.729           ms/op
Client.listUser:listUser·p0.50        sample          7.946           ms/op
Client.listUser:listUser·p0.90        sample         11.649           ms/op
Client.listUser:listUser·p0.95        sample         13.189           ms/op
Client.listUser:listUser·p0.99        sample         19.398           ms/op
Client.listUser:listUser·p0.999       sample         25.834           ms/op
Client.listUser:listUser·p0.9999      sample         27.722           ms/op
Client.listUser:listUser·p1.00        sample         27.722           ms/op
