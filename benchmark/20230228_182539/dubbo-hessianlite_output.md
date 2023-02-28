# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.020 ops/ms
Iteration   1: 3.006 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.006 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.745 ops/ms
Iteration   1: 7.434 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.434 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
Iteration   1: 4.965 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.965 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.831 ops/ms
Iteration   1: 1.438 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.438 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 19.642 ±(99.9%) 0.683 ms/op
Iteration   1: 8.491 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.265 ±(99.9%) 0.087 ms/op
Iteration   1: 4.202 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.517 ±(99.9%) 0.146 ms/op
Iteration   1: 5.078 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.078 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.264 ±(99.9%) 0.367 ms/op
Iteration   1: 16.666 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.666 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.831 ±(99.9%) 0.326 ms/op
Iteration   1: 6.511 ±(99.9%) 0.105 ms/op
                 createUser·p0.00:   1.847 ms/op
                 createUser·p0.50:   6.423 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   7.913 ms/op
                 createUser·p0.99:   12.321 ms/op
                 createUser·p0.999:  31.523 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5000
  mean =      6.511 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 60 
    [ 5.000,  7.500) = 4647 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.847 ms/op
     p(50.0000) =      6.423 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     31.523 ms/op
     p(99.9900) =     31.556 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.444 ±(99.9%) 0.206 ms/op
Iteration   1: 3.146 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.627 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  13.582 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10167
  mean =      3.146 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 102 
    [ 2.500,  3.750) = 9615 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.627 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.387 ±(99.9%) 0.317 ms/op
Iteration   1: 4.338 ±(99.9%) 0.073 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   11.646 ms/op
                 getUser·p0.999:  25.796 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7379
  mean =      4.338 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 6341 
    [ 5.000,  7.500) = 851 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =     11.646 ms/op
     p(99.9000) =     25.796 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.761 ±(99.9%) 0.637 ms/op
Iteration   1: 15.687 ±(99.9%) 0.202 ms/op
                 listUser·p0.00:   7.520 ms/op
                 listUser·p0.50:   15.213 ms/op
                 listUser·p0.90:   16.738 ms/op
                 listUser·p0.95:   17.606 ms/op
                 listUser·p0.99:   30.251 ms/op
                 listUser·p0.999:  36.301 ms/op
                 listUser·p0.9999: 36.307 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2046
  mean =     15.687 ±(99.9%) 0.202 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 822 
    [15.000, 17.500) = 1088 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      7.520 ms/op
     p(50.0000) =     15.213 ms/op
     p(90.0000) =     16.738 ms/op
     p(95.0000) =     17.606 ms/op
     p(99.0000) =     30.251 ms/op
     p(99.9000) =     36.301 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.006          ops/ms
Client.existUser                       thrpt          7.434          ops/ms
Client.getUser                         thrpt          4.965          ops/ms
Client.listUser                        thrpt          1.438          ops/ms
Client.createUser                       avgt          8.491           ms/op
Client.existUser                        avgt          4.202           ms/op
Client.getUser                          avgt          5.078           ms/op
Client.listUser                         avgt         16.666           ms/op
Client.createUser                     sample   5000   6.511 ± 0.105   ms/op
Client.createUser:createUser·p0.00    sample          1.847           ms/op
Client.createUser:createUser·p0.50    sample          6.423           ms/op
Client.createUser:createUser·p0.90    sample          7.053           ms/op
Client.createUser:createUser·p0.95    sample          7.913           ms/op
Client.createUser:createUser·p0.99    sample         12.321           ms/op
Client.createUser:createUser·p0.999   sample         31.523           ms/op
Client.createUser:createUser·p0.9999  sample         31.556           ms/op
Client.createUser:createUser·p1.00    sample         31.556           ms/op
Client.existUser                      sample  10167   3.146 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.988           ms/op
Client.existUser:existUser·p0.50      sample          3.015           ms/op
Client.existUser:existUser·p0.90      sample          3.314           ms/op
Client.existUser:existUser·p0.95      sample          3.627           ms/op
Client.existUser:existUser·p0.99      sample          9.388           ms/op
Client.existUser:existUser·p0.999     sample         13.582           ms/op
Client.existUser:existUser·p0.9999    sample         13.615           ms/op
Client.existUser:existUser·p1.00      sample         13.615           ms/op
Client.getUser                        sample   7379   4.338 ± 0.073   ms/op
Client.getUser:getUser·p0.00          sample          1.767           ms/op
Client.getUser:getUser·p0.50          sample          4.116           ms/op
Client.getUser:getUser·p0.90          sample          5.243           ms/op
Client.getUser:getUser·p0.95          sample          5.882           ms/op
Client.getUser:getUser·p0.99          sample         11.646           ms/op
Client.getUser:getUser·p0.999         sample         25.796           ms/op
Client.getUser:getUser·p0.9999        sample         26.509           ms/op
Client.getUser:getUser·p1.00          sample         26.509           ms/op
Client.listUser                       sample   2046  15.687 ± 0.202   ms/op
Client.listUser:listUser·p0.00        sample          7.520           ms/op
Client.listUser:listUser·p0.50        sample         15.213           ms/op
Client.listUser:listUser·p0.90        sample         16.738           ms/op
Client.listUser:listUser·p0.95        sample         17.606           ms/op
Client.listUser:listUser·p0.99        sample         30.251           ms/op
Client.listUser:listUser·p0.999       sample         36.301           ms/op
Client.listUser:listUser·p0.9999      sample         36.307           ms/op
Client.listUser:listUser·p1.00        sample         36.307           ms/op
