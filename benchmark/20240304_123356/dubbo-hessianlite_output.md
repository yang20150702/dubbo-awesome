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
# Warmup Iteration   1: 2.437 ops/ms
Iteration   1: 6.412 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.412 ops/ms


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
# Warmup Iteration   1: 5.912 ops/ms
Iteration   1: 11.216 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.216 ops/ms


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
# Warmup Iteration   1: 4.388 ops/ms
Iteration   1: 7.258 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.258 ops/ms


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
# Warmup Iteration   1: 1.908 ops/ms
Iteration   1: 3.405 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.405 ops/ms


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
# Warmup Iteration   1: 5.373 ±(99.9%) 0.058 ms/op
Iteration   1: 3.210 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.210 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.028 ms/op
Iteration   1: 1.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 5.481 ±(99.9%) 0.081 ms/op
Iteration   1: 3.072 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.072 ms/op


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
# Warmup Iteration   1: 13.745 ±(99.9%) 0.303 ms/op
Iteration   1: 8.837 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.837 ms/op


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.093 ms/op
Iteration   1: 2.822 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.736 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  7.864 ms/op
                 createUser·p0.9999: 8.554 ms/op
                 createUser·p1.00:   8.569 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11498
  mean =      2.822 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 39 
    [1.500, 2.000) = 557 
    [2.000, 2.500) = 3132 
    [2.500, 3.000) = 4011 
    [3.000, 3.500) = 2637 
    [3.500, 4.000) = 755 
    [4.000, 4.500) = 134 
    [4.500, 5.000) = 81 
    [5.000, 5.500) = 31 
    [5.500, 6.000) = 55 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 28 
    [7.000, 7.500) = 14 
    [7.500, 8.000) = 11 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =      8.554 ms/op
     p(99.9990) =      8.569 ms/op
     p(99.9999) =      8.569 ms/op
    p(100.0000) =      8.569 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.070 ms/op
Iteration   1: 1.901 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   1.773 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.132 ms/op
                 existUser·p0.999:  30.053 ms/op
                 existUser·p0.9999: 30.931 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16864
  mean =      1.901 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15769 
    [ 2.500,  5.000) = 1031 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.773 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.132 ms/op
     p(99.9000) =     30.053 ms/op
     p(99.9900) =     30.931 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.113 ms/op
Iteration   1: 3.271 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.109 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.555 ms/op
                 getUser·p0.999:  8.685 ms/op
                 getUser·p0.9999: 9.830 ms/op
                 getUser·p1.00:   9.830 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9777
  mean =      3.271 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 247 
    [ 2.000,  3.000) = 3453 
    [ 3.000,  4.000) = 4845 
    [ 4.000,  5.000) = 1075 
    [ 5.000,  6.000) = 84 
    [ 6.000,  7.000) = 18 
    [ 7.000,  8.000) = 36 
    [ 8.000,  9.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.109 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.555 ms/op
     p(99.9000) =      8.685 ms/op
     p(99.9900) =      9.830 ms/op
     p(99.9990) =      9.830 ms/op
     p(99.9999) =      9.830 ms/op
    p(100.0000) =      9.830 ms/op


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
# Warmup Iteration   1: 15.141 ±(99.9%) 0.946 ms/op
Iteration   1: 9.739 ±(99.9%) 0.201 ms/op
                 listUser·p0.00:   4.071 ms/op
                 listUser·p0.50:   8.880 ms/op
                 listUser·p0.90:   13.238 ms/op
                 listUser·p0.95:   15.453 ms/op
                 listUser·p0.99:   23.563 ms/op
                 listUser·p0.999:  35.136 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3311
  mean =      9.739 ±(99.9%) 0.201 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 22 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 1481 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.071 ms/op
     p(50.0000) =      8.880 ms/op
     p(90.0000) =     13.238 ms/op
     p(95.0000) =     15.453 ms/op
     p(99.0000) =     23.563 ms/op
     p(99.9000) =     35.136 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.412          ops/ms
Client.existUser                       thrpt         11.216          ops/ms
Client.getUser                         thrpt          7.258          ops/ms
Client.listUser                        thrpt          3.405          ops/ms
Client.createUser                       avgt          3.210           ms/op
Client.existUser                        avgt          1.867           ms/op
Client.getUser                          avgt          3.072           ms/op
Client.listUser                         avgt          8.837           ms/op
Client.createUser                     sample  11498   2.822 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.012           ms/op
Client.createUser:createUser·p0.50    sample          2.736           ms/op
Client.createUser:createUser·p0.90    sample          3.490           ms/op
Client.createUser:createUser·p0.95    sample          3.797           ms/op
Client.createUser:createUser·p0.99    sample          5.521           ms/op
Client.createUser:createUser·p0.999   sample          7.864           ms/op
Client.createUser:createUser·p0.9999  sample          8.554           ms/op
Client.createUser:createUser·p1.00    sample          8.569           ms/op
Client.existUser                      sample  16864   1.901 ± 0.036   ms/op
Client.existUser:existUser·p0.00      sample          0.483           ms/op
Client.existUser:existUser·p0.50      sample          1.773           ms/op
Client.existUser:existUser·p0.90      sample          2.372           ms/op
Client.existUser:existUser·p0.95      sample          2.589           ms/op
Client.existUser:existUser·p0.99      sample          3.132           ms/op
Client.existUser:existUser·p0.999     sample         30.053           ms/op
Client.existUser:existUser·p0.9999    sample         30.931           ms/op
Client.existUser:existUser·p1.00      sample         30.999           ms/op
Client.getUser                        sample   9777   3.271 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.801           ms/op
Client.getUser:getUser·p0.50          sample          3.236           ms/op
Client.getUser:getUser·p0.90          sample          4.109           ms/op
Client.getUser:getUser·p0.95          sample          4.424           ms/op
Client.getUser:getUser·p0.99          sample          5.555           ms/op
Client.getUser:getUser·p0.999         sample          8.685           ms/op
Client.getUser:getUser·p0.9999        sample          9.830           ms/op
Client.getUser:getUser·p1.00          sample          9.830           ms/op
Client.listUser                       sample   3311   9.739 ± 0.201   ms/op
Client.listUser:listUser·p0.00        sample          4.071           ms/op
Client.listUser:listUser·p0.50        sample          8.880           ms/op
Client.listUser:listUser·p0.90        sample         13.238           ms/op
Client.listUser:listUser·p0.95        sample         15.453           ms/op
Client.listUser:listUser·p0.99        sample         23.563           ms/op
Client.listUser:listUser·p0.999       sample         35.136           ms/op
Client.listUser:listUser·p0.9999      sample         36.045           ms/op
Client.listUser:listUser·p1.00        sample         36.045           ms/op
