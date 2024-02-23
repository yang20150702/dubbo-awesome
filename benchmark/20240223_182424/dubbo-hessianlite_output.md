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
# Warmup Iteration   1: 2.220 ops/ms
Iteration   1: 5.822 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.822 ops/ms


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
# Warmup Iteration   1: 5.441 ops/ms
Iteration   1: 11.563 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.563 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ops/ms
Iteration   1: 8.027 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.027 ops/ms


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
# Warmup Iteration   1: 1.916 ops/ms
Iteration   1: 3.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.365 ops/ms


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
# Warmup Iteration   1: 5.691 ±(99.9%) 0.108 ms/op
Iteration   1: 3.408 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.408 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.033 ms/op
Iteration   1: 2.010 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.062 ms/op
Iteration   1: 3.325 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.325 ms/op


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
# Warmup Iteration   1: 13.032 ±(99.9%) 0.278 ms/op
Iteration   1: 8.384 ±(99.9%) 0.140 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.384 ms/op


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
# Warmup Iteration   1: 5.773 ±(99.9%) 0.167 ms/op
Iteration   1: 3.355 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  26.051 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9528
  mean =      3.355 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 615 
    [ 2.500,  5.000) = 8530 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     26.051 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 3.203 ±(99.9%) 0.090 ms/op
Iteration   1: 2.061 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   1.935 ms/op
                 existUser·p0.90:   2.785 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 9.877 ms/op
                 existUser·p1.00:   9.978 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15568
  mean =      2.061 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 92 
    [ 1.000,  2.000) = 8564 
    [ 2.000,  3.000) = 6160 
    [ 3.000,  4.000) = 618 
    [ 4.000,  5.000) = 67 
    [ 5.000,  6.000) = 59 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.935 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      5.603 ms/op
     p(99.9900) =      9.877 ms/op
     p(99.9990) =      9.978 ms/op
     p(99.9999) =      9.978 ms/op
    p(100.0000) =      9.978 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.988 ±(99.9%) 0.130 ms/op
Iteration   1: 3.146 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.713 ms/op
                 getUser·p0.999:  9.186 ms/op
                 getUser·p0.9999: 10.321 ms/op
                 getUser·p1.00:   10.322 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10165
  mean =      3.146 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 149 
    [ 2.000,  3.000) = 5306 
    [ 3.000,  4.000) = 3716 
    [ 4.000,  5.000) = 760 
    [ 5.000,  6.000) = 142 
    [ 6.000,  7.000) = 59 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 10 
    [ 9.000, 10.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.713 ms/op
     p(99.9000) =      9.186 ms/op
     p(99.9900) =     10.321 ms/op
     p(99.9990) =     10.322 ms/op
     p(99.9999) =     10.322 ms/op
    p(100.0000) =     10.322 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.181 ±(99.9%) 0.362 ms/op
Iteration   1: 9.556 ±(99.9%) 0.144 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   9.191 ms/op
                 listUser·p0.90:   12.665 ms/op
                 listUser·p0.95:   13.810 ms/op
                 listUser·p0.99:   17.952 ms/op
                 listUser·p0.999:  22.151 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3340
  mean =      9.556 ±(99.9%) 0.144 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 49 
    [ 5.000,  7.500) = 540 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 841 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.072 ms/op
     p(50.0000) =      9.191 ms/op
     p(90.0000) =     12.665 ms/op
     p(95.0000) =     13.810 ms/op
     p(99.0000) =     17.952 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.822          ops/ms
Client.existUser                       thrpt         11.563          ops/ms
Client.getUser                         thrpt          8.027          ops/ms
Client.listUser                        thrpt          3.365          ops/ms
Client.createUser                       avgt          3.408           ms/op
Client.existUser                        avgt          2.010           ms/op
Client.getUser                          avgt          3.325           ms/op
Client.listUser                         avgt          8.384           ms/op
Client.createUser                     sample   9528   3.355 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.227           ms/op
Client.createUser:createUser·p0.50    sample          3.035           ms/op
Client.createUser:createUser·p0.90    sample          4.219           ms/op
Client.createUser:createUser·p0.95    sample          4.784           ms/op
Client.createUser:createUser·p0.99    sample          8.045           ms/op
Client.createUser:createUser·p0.999   sample         26.051           ms/op
Client.createUser:createUser·p0.9999  sample         26.214           ms/op
Client.createUser:createUser·p1.00    sample         26.214           ms/op
Client.existUser                      sample  15568   2.061 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.500           ms/op
Client.existUser:existUser·p0.50      sample          1.935           ms/op
Client.existUser:existUser·p0.90      sample          2.785           ms/op
Client.existUser:existUser·p0.95      sample          2.994           ms/op
Client.existUser:existUser·p0.99      sample          3.781           ms/op
Client.existUser:existUser·p0.999     sample          5.603           ms/op
Client.existUser:existUser·p0.9999    sample          9.877           ms/op
Client.existUser:existUser·p1.00      sample          9.978           ms/op
Client.getUser                        sample  10165   3.146 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.999           ms/op
Client.getUser:getUser·p0.50          sample          2.929           ms/op
Client.getUser:getUser·p0.90          sample          3.990           ms/op
Client.getUser:getUser·p0.95          sample          4.375           ms/op
Client.getUser:getUser·p0.99          sample          5.713           ms/op
Client.getUser:getUser·p0.999         sample          9.186           ms/op
Client.getUser:getUser·p0.9999        sample         10.321           ms/op
Client.getUser:getUser·p1.00          sample         10.322           ms/op
Client.listUser                       sample   3340   9.556 ± 0.144   ms/op
Client.listUser:listUser·p0.00        sample          3.072           ms/op
Client.listUser:listUser·p0.50        sample          9.191           ms/op
Client.listUser:listUser·p0.90        sample         12.665           ms/op
Client.listUser:listUser·p0.95        sample         13.810           ms/op
Client.listUser:listUser·p0.99        sample         17.952           ms/op
Client.listUser:listUser·p0.999       sample         22.151           ms/op
Client.listUser:listUser·p0.9999      sample         22.413           ms/op
Client.listUser:listUser·p1.00        sample         22.413           ms/op
