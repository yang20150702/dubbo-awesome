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
# Warmup Iteration   1: 2.267 ops/ms
Iteration   1: 5.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.695 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.315 ops/ms
Iteration   1: 11.765 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.765 ops/ms


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
# Warmup Iteration   1: 4.410 ops/ms
Iteration   1: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.841 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.836 ops/ms
Iteration   1: 3.343 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.343 ops/ms


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.073 ms/op
Iteration   1: 2.948 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.948 ms/op


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
# Warmup Iteration   1: 3.460 ±(99.9%) 0.042 ms/op
Iteration   1: 2.027 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.027 ms/op


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
# Warmup Iteration   1: 4.905 ±(99.9%) 0.055 ms/op
Iteration   1: 3.005 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.005 ms/op


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
# Warmup Iteration   1: 11.461 ±(99.9%) 0.216 ms/op
Iteration   1: 8.027 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.027 ms/op


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
# Warmup Iteration   1: 5.226 ±(99.9%) 0.122 ms/op
Iteration   1: 3.431 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   13.593 ms/op
                 createUser·p0.999:  18.301 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9316
  mean =      3.431 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 722 
    [ 2.500,  5.000) = 8364 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =     13.593 ms/op
     p(99.9000) =     18.301 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.076 ms/op
Iteration   1: 1.732 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   1.952 ms/op
                 existUser·p0.95:   2.138 ms/op
                 existUser·p0.99:   2.951 ms/op
                 existUser·p0.999:  24.954 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18456
  mean =      1.732 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18155 
    [ 2.500,  5.000) = 248 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      1.952 ms/op
     p(95.0000) =      2.138 ms/op
     p(99.0000) =      2.951 ms/op
     p(99.9000) =     24.954 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.104 ms/op
Iteration   1: 3.011 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.760 ms/op
                 getUser·p0.9999: 10.172 ms/op
                 getUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10635
  mean =      3.011 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 435 
    [ 2.000,  3.000) = 5065 
    [ 3.000,  4.000) = 4323 
    [ 4.000,  5.000) = 676 
    [ 5.000,  6.000) = 94 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =      9.760 ms/op
     p(99.9900) =     10.172 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


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
# Warmup Iteration   1: 11.187 ±(99.9%) 0.379 ms/op
Iteration   1: 7.657 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   7.365 ms/op
                 listUser·p0.90:   9.804 ms/op
                 listUser·p0.95:   10.830 ms/op
                 listUser·p0.99:   18.492 ms/op
                 listUser·p0.999:  20.961 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4165
  mean =      7.657 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 192 
    [ 5.000,  7.500) = 2012 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      7.365 ms/op
     p(90.0000) =      9.804 ms/op
     p(95.0000) =     10.830 ms/op
     p(99.0000) =     18.492 ms/op
     p(99.9000) =     20.961 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.695          ops/ms
Client.existUser                       thrpt         11.765          ops/ms
Client.getUser                         thrpt          7.841          ops/ms
Client.listUser                        thrpt          3.343          ops/ms
Client.createUser                       avgt          2.948           ms/op
Client.existUser                        avgt          2.027           ms/op
Client.getUser                          avgt          3.005           ms/op
Client.listUser                         avgt          8.027           ms/op
Client.createUser                     sample   9316   3.431 ± 0.053   ms/op
Client.createUser:createUser·p0.00    sample          1.002           ms/op
Client.createUser:createUser·p0.50    sample          3.240           ms/op
Client.createUser:createUser·p0.90    sample          3.977           ms/op
Client.createUser:createUser·p0.95    sample          4.358           ms/op
Client.createUser:createUser·p0.99    sample         13.593           ms/op
Client.createUser:createUser·p0.999   sample         18.301           ms/op
Client.createUser:createUser·p0.9999  sample         20.644           ms/op
Client.createUser:createUser·p1.00    sample         20.644           ms/op
Client.existUser                      sample  18456   1.732 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.545           ms/op
Client.existUser:existUser·p0.50      sample          1.665           ms/op
Client.existUser:existUser·p0.90      sample          1.952           ms/op
Client.existUser:existUser·p0.95      sample          2.138           ms/op
Client.existUser:existUser·p0.99      sample          2.951           ms/op
Client.existUser:existUser·p0.999     sample         24.954           ms/op
Client.existUser:existUser·p0.9999    sample         25.461           ms/op
Client.existUser:existUser·p1.00      sample         25.461           ms/op
Client.getUser                        sample  10635   3.011 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.844           ms/op
Client.getUser:getUser·p0.50          sample          2.978           ms/op
Client.getUser:getUser·p0.90          sample          3.834           ms/op
Client.getUser:getUser·p0.95          sample          4.162           ms/op
Client.getUser:getUser·p0.99          sample          5.333           ms/op
Client.getUser:getUser·p0.999         sample          9.760           ms/op
Client.getUser:getUser·p0.9999        sample         10.172           ms/op
Client.getUser:getUser·p1.00          sample         10.174           ms/op
Client.listUser                       sample   4165   7.657 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          1.047           ms/op
Client.listUser:listUser·p0.50        sample          7.365           ms/op
Client.listUser:listUser·p0.90        sample          9.804           ms/op
Client.listUser:listUser·p0.95        sample         10.830           ms/op
Client.listUser:listUser·p0.99        sample         18.492           ms/op
Client.listUser:listUser·p0.999       sample         20.961           ms/op
Client.listUser:listUser·p0.9999      sample         22.184           ms/op
Client.listUser:listUser·p1.00        sample         22.184           ms/op
