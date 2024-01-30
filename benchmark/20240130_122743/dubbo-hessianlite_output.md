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
# Warmup Iteration   1: 2.440 ops/ms
Iteration   1: 6.649 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.649 ops/ms


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
# Warmup Iteration   1: 5.584 ops/ms
Iteration   1: 11.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.386 ops/ms


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
# Warmup Iteration   1: 4.098 ops/ms
Iteration   1: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.240 ops/ms


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
# Warmup Iteration   1: 2.146 ops/ms
Iteration   1: 3.338 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.338 ops/ms


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
# Warmup Iteration   1: 5.326 ±(99.9%) 0.074 ms/op
Iteration   1: 3.267 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.267 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.037 ms/op
Iteration   1: 1.859 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.859 ms/op


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
# Warmup Iteration   1: 6.039 ±(99.9%) 0.096 ms/op
Iteration   1: 3.415 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.415 ms/op


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
# Warmup Iteration   1: 12.807 ±(99.9%) 0.210 ms/op
Iteration   1: 8.140 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.140 ms/op


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
# Warmup Iteration   1: 5.244 ±(99.9%) 0.121 ms/op
Iteration   1: 3.029 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.594 ms/op
                 createUser·p0.999:  33.161 ms/op
                 createUser·p0.9999: 34.778 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10554
  mean =      3.029 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2203 
    [ 2.500,  5.000) = 8146 
    [ 5.000,  7.500) = 113 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.594 ms/op
     p(99.9000) =     33.161 ms/op
     p(99.9900) =     34.778 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.084 ms/op
Iteration   1: 2.008 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.162 ms/op
                 existUser·p0.999:  6.136 ms/op
                 existUser·p0.9999: 7.368 ms/op
                 existUser·p1.00:   7.471 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16002
  mean =      2.008 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 80 
    [1.000, 1.500) = 1469 
    [1.500, 2.000) = 7088 
    [2.000, 2.500) = 5375 
    [2.500, 3.000) = 1586 
    [3.000, 3.500) = 313 
    [3.500, 4.000) = 29 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 11 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.162 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =      7.368 ms/op
     p(99.9990) =      7.471 ms/op
     p(99.9999) =      7.471 ms/op
    p(100.0000) =      7.471 ms/op


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
# Warmup Iteration   1: 4.711 ±(99.9%) 0.128 ms/op
Iteration   1: 2.736 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 18.213 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11694
  mean =      2.736 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 5214 
    [ 2.500,  3.750) = 5885 
    [ 3.750,  5.000) = 446 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     18.213 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 12.866 ±(99.9%) 0.457 ms/op
Iteration   1: 8.212 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   3.101 ms/op
                 listUser·p0.50:   7.766 ms/op
                 listUser·p0.90:   10.768 ms/op
                 listUser·p0.95:   11.872 ms/op
                 listUser·p0.99:   17.674 ms/op
                 listUser·p0.999:  25.832 ms/op
                 listUser·p0.9999: 27.460 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3887
  mean =      8.212 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 113 
    [ 5.000,  7.500) = 1537 
    [ 7.500, 10.000) = 1623 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      3.101 ms/op
     p(50.0000) =      7.766 ms/op
     p(90.0000) =     10.768 ms/op
     p(95.0000) =     11.872 ms/op
     p(99.0000) =     17.674 ms/op
     p(99.9000) =     25.832 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.649          ops/ms
Client.existUser                       thrpt         11.386          ops/ms
Client.getUser                         thrpt          8.240          ops/ms
Client.listUser                        thrpt          3.338          ops/ms
Client.createUser                       avgt          3.267           ms/op
Client.existUser                        avgt          1.859           ms/op
Client.getUser                          avgt          3.415           ms/op
Client.listUser                         avgt          8.140           ms/op
Client.createUser                     sample  10554   3.029 ± 0.061   ms/op
Client.createUser:createUser·p0.00    sample          1.210           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.711           ms/op
Client.createUser:createUser·p0.95    sample          4.219           ms/op
Client.createUser:createUser·p0.99    sample          6.594           ms/op
Client.createUser:createUser·p0.999   sample         33.161           ms/op
Client.createUser:createUser·p0.9999  sample         34.778           ms/op
Client.createUser:createUser·p1.00    sample         34.800           ms/op
Client.existUser                      sample  16002   2.008 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.460           ms/op
Client.existUser:existUser·p0.50      sample          1.968           ms/op
Client.existUser:existUser·p0.90      sample          2.589           ms/op
Client.existUser:existUser·p0.95      sample          2.822           ms/op
Client.existUser:existUser·p0.99      sample          3.162           ms/op
Client.existUser:existUser·p0.999     sample          6.136           ms/op
Client.existUser:existUser·p0.9999    sample          7.368           ms/op
Client.existUser:existUser·p1.00      sample          7.471           ms/op
Client.getUser                        sample  11694   2.736 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          1.135           ms/op
Client.getUser:getUser·p0.50          sample          2.556           ms/op
Client.getUser:getUser·p0.90          sample          3.408           ms/op
Client.getUser:getUser·p0.95          sample          3.760           ms/op
Client.getUser:getUser·p0.99          sample          5.407           ms/op
Client.getUser:getUser·p0.999         sample         17.334           ms/op
Client.getUser:getUser·p0.9999        sample         18.213           ms/op
Client.getUser:getUser·p1.00          sample         18.252           ms/op
Client.listUser                       sample   3887   8.212 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          3.101           ms/op
Client.listUser:listUser·p0.50        sample          7.766           ms/op
Client.listUser:listUser·p0.90        sample         10.768           ms/op
Client.listUser:listUser·p0.95        sample         11.872           ms/op
Client.listUser:listUser·p0.99        sample         17.674           ms/op
Client.listUser:listUser·p0.999       sample         25.832           ms/op
Client.listUser:listUser·p0.9999      sample         27.460           ms/op
Client.listUser:listUser·p1.00        sample         27.460           ms/op
