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
# Warmup Iteration   1: 2.712 ops/ms
Iteration   1: 6.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.352 ops/ms


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
# Warmup Iteration   1: 6.196 ops/ms
Iteration   1: 11.823 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.823 ops/ms


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
# Warmup Iteration   1: 4.336 ops/ms
Iteration   1: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.421 ops/ms


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
# Warmup Iteration   1: 2.269 ops/ms
Iteration   1: 3.063 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.063 ops/ms


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
# Warmup Iteration   1: 5.650 ±(99.9%) 0.061 ms/op
Iteration   1: 3.185 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.185 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.035 ms/op
Iteration   1: 2.043 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.043 ms/op


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
# Warmup Iteration   1: 5.158 ±(99.9%) 0.059 ms/op
Iteration   1: 3.279 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.279 ms/op


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
# Warmup Iteration   1: 13.556 ±(99.9%) 0.257 ms/op
Iteration   1: 8.432 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.432 ms/op


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.104 ms/op
Iteration   1: 2.872 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.840 ms/op
                 createUser·p0.99:   4.834 ms/op
                 createUser·p0.999:  17.688 ms/op
                 createUser·p0.9999: 22.742 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11190
  mean =      2.872 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2375 
    [ 2.500,  5.000) = 8730 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.840 ms/op
     p(99.0000) =      4.834 ms/op
     p(99.9000) =     17.688 ms/op
     p(99.9900) =     22.742 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.071 ms/op
Iteration   1: 2.019 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   1.874 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.931 ms/op
                 existUser·p0.999:  16.630 ms/op
                 existUser·p0.9999: 18.455 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15887
  mean =      2.019 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 14575 
    [ 2.500,  3.750) = 965 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.931 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     18.455 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.104 ms/op
Iteration   1: 3.140 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.609 ms/op
                 getUser·p0.999:  7.445 ms/op
                 getUser·p0.9999: 10.922 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10216
  mean =      3.140 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 189 
    [ 2.000,  3.000) = 4473 
    [ 3.000,  4.000) = 4574 
    [ 4.000,  5.000) = 766 
    [ 5.000,  6.000) = 145 
    [ 6.000,  7.000) = 32 
    [ 7.000,  8.000) = 36 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.609 ms/op
     p(99.9000) =      7.445 ms/op
     p(99.9900) =     10.922 ms/op
     p(99.9990) =     10.994 ms/op
     p(99.9999) =     10.994 ms/op
    p(100.0000) =     10.994 ms/op


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
# Warmup Iteration   1: 12.382 ±(99.9%) 0.392 ms/op
Iteration   1: 10.237 ±(99.9%) 0.445 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   8.798 ms/op
                 listUser·p0.90:   12.911 ms/op
                 listUser·p0.95:   15.102 ms/op
                 listUser·p0.99:   53.251 ms/op
                 listUser·p0.999:  69.593 ms/op
                 listUser·p0.9999: 74.580 ms/op
                 listUser·p1.00:   74.580 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3144
  mean =     10.237 ±(99.9%) 0.445 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 122 
    [ 5.000, 10.000) = 2053 
    [10.000, 15.000) = 802 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 9 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 10 
    [50.000, 55.000) = 36 
    [55.000, 60.000) = 18 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      8.798 ms/op
     p(90.0000) =     12.911 ms/op
     p(95.0000) =     15.102 ms/op
     p(99.0000) =     53.251 ms/op
     p(99.9000) =     69.593 ms/op
     p(99.9900) =     74.580 ms/op
     p(99.9990) =     74.580 ms/op
     p(99.9999) =     74.580 ms/op
    p(100.0000) =     74.580 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.352          ops/ms
Client.existUser                       thrpt         11.823          ops/ms
Client.getUser                         thrpt          8.421          ops/ms
Client.listUser                        thrpt          3.063          ops/ms
Client.createUser                       avgt          3.185           ms/op
Client.existUser                        avgt          2.043           ms/op
Client.getUser                          avgt          3.279           ms/op
Client.listUser                         avgt          8.432           ms/op
Client.createUser                     sample  11190   2.872 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.405           ms/op
Client.createUser:createUser·p0.50    sample          2.728           ms/op
Client.createUser:createUser·p0.90    sample          3.490           ms/op
Client.createUser:createUser·p0.95    sample          3.840           ms/op
Client.createUser:createUser·p0.99    sample          4.834           ms/op
Client.createUser:createUser·p0.999   sample         17.688           ms/op
Client.createUser:createUser·p0.9999  sample         22.742           ms/op
Client.createUser:createUser·p1.00    sample         23.101           ms/op
Client.existUser                      sample  15887   2.019 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.702           ms/op
Client.existUser:existUser·p0.50      sample          1.874           ms/op
Client.existUser:existUser·p0.90      sample          2.404           ms/op
Client.existUser:existUser·p0.95      sample          2.605           ms/op
Client.existUser:existUser·p0.99      sample          3.931           ms/op
Client.existUser:existUser·p0.999     sample         16.630           ms/op
Client.existUser:existUser·p0.9999    sample         18.455           ms/op
Client.existUser:existUser·p1.00      sample         19.497           ms/op
Client.getUser                        sample  10216   3.140 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.247           ms/op
Client.getUser:getUser·p0.50          sample          3.072           ms/op
Client.getUser:getUser·p0.90          sample          3.985           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          5.609           ms/op
Client.getUser:getUser·p0.999         sample          7.445           ms/op
Client.getUser:getUser·p0.9999        sample         10.922           ms/op
Client.getUser:getUser·p1.00          sample         10.994           ms/op
Client.listUser                       sample   3144  10.237 ± 0.445   ms/op
Client.listUser:listUser·p0.00        sample          1.073           ms/op
Client.listUser:listUser·p0.50        sample          8.798           ms/op
Client.listUser:listUser·p0.90        sample         12.911           ms/op
Client.listUser:listUser·p0.95        sample         15.102           ms/op
Client.listUser:listUser·p0.99        sample         53.251           ms/op
Client.listUser:listUser·p0.999       sample         69.593           ms/op
Client.listUser:listUser·p0.9999      sample         74.580           ms/op
Client.listUser:listUser·p1.00        sample         74.580           ms/op
