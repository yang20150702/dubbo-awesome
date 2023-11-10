# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.516 ops/ms
Iteration   1: 3.991 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.991 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ops/ms
Iteration   1: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.689 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.347 ops/ms
Iteration   1: 4.898 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.898 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.114 ops/ms
Iteration   1: 1.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.614 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.258 ±(99.9%) 0.416 ms/op
Iteration   1: 4.978 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.780 ±(99.9%) 0.120 ms/op
Iteration   1: 2.576 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.576 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.117 ±(99.9%) 0.198 ms/op
Iteration   1: 5.858 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.858 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 27.303 ±(99.9%) 0.506 ms/op
Iteration   1: 19.924 ±(99.9%) 0.279 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.559 ±(99.9%) 0.286 ms/op
Iteration   1: 3.642 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.802 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   7.331 ms/op
                 createUser·p0.99:   15.204 ms/op
                 createUser·p0.999:  20.513 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8800
  mean =      3.642 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2327 
    [ 2.500,  5.000) = 5250 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      7.331 ms/op
     p(99.0000) =     15.204 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.491 ±(99.9%) 0.183 ms/op
Iteration   1: 2.613 ±(99.9%) 0.060 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   12.056 ms/op
                 existUser·p0.999:  26.083 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12214
  mean =      2.613 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8890 
    [ 2.500,  5.000) = 2673 
    [ 5.000,  7.500) = 314 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =     12.056 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.631 ±(99.9%) 0.308 ms/op
Iteration   1: 3.779 ±(99.9%) 0.075 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   4.996 ms/op
                 getUser·p0.95:   6.726 ms/op
                 getUser·p0.99:   13.148 ms/op
                 getUser·p0.999:  27.992 ms/op
                 getUser·p0.9999: 29.753 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8550
  mean =      3.779 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 297 
    [ 2.500,  5.000) = 7403 
    [ 5.000,  7.500) = 536 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.996 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =     13.148 ms/op
     p(99.9000) =     27.992 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.779 ±(99.9%) 0.787 ms/op
Iteration   1: 15.615 ±(99.9%) 0.359 ms/op
                 listUser·p0.00:   5.693 ms/op
                 listUser·p0.50:   14.557 ms/op
                 listUser·p0.90:   21.407 ms/op
                 listUser·p0.95:   25.461 ms/op
                 listUser·p0.99:   35.586 ms/op
                 listUser·p0.999:  41.143 ms/op
                 listUser·p0.9999: 41.484 ms/op
                 listUser·p1.00:   41.484 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2066
  mean =     15.615 ±(99.9%) 0.359 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 104 
    [10.000, 15.000) = 1022 
    [15.000, 20.000) = 636 
    [20.000, 25.000) = 192 
    [25.000, 30.000) = 70 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      5.693 ms/op
     p(50.0000) =     14.557 ms/op
     p(90.0000) =     21.407 ms/op
     p(95.0000) =     25.461 ms/op
     p(99.0000) =     35.586 ms/op
     p(99.9000) =     41.143 ms/op
     p(99.9900) =     41.484 ms/op
     p(99.9990) =     41.484 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.991          ops/ms
Client.existUser                       thrpt         10.689          ops/ms
Client.getUser                         thrpt          4.898          ops/ms
Client.listUser                        thrpt          1.614          ops/ms
Client.createUser                       avgt          4.978           ms/op
Client.existUser                        avgt          2.576           ms/op
Client.getUser                          avgt          5.858           ms/op
Client.listUser                         avgt         19.924           ms/op
Client.createUser                     sample   8800   3.642 ± 0.080   ms/op
Client.createUser:createUser·p0.00    sample          0.951           ms/op
Client.createUser:createUser·p0.50    sample          2.802           ms/op
Client.createUser:createUser·p0.90    sample          5.505           ms/op
Client.createUser:createUser·p0.95    sample          7.331           ms/op
Client.createUser:createUser·p0.99    sample         15.204           ms/op
Client.createUser:createUser·p0.999   sample         20.513           ms/op
Client.createUser:createUser·p0.9999  sample         25.494           ms/op
Client.createUser:createUser·p1.00    sample         25.494           ms/op
Client.existUser                      sample  12214   2.613 ± 0.060   ms/op
Client.existUser:existUser·p0.00      sample          0.930           ms/op
Client.existUser:existUser·p0.50      sample          1.978           ms/op
Client.existUser:existUser·p0.90      sample          3.908           ms/op
Client.existUser:existUser·p0.95      sample          5.358           ms/op
Client.existUser:existUser·p0.99      sample         12.056           ms/op
Client.existUser:existUser·p0.999     sample         26.083           ms/op
Client.existUser:existUser·p0.9999    sample         26.149           ms/op
Client.existUser:existUser·p1.00      sample         26.149           ms/op
Client.getUser                        sample   8550   3.779 ± 0.075   ms/op
Client.getUser:getUser·p0.00          sample          0.864           ms/op
Client.getUser:getUser·p0.50          sample          3.256           ms/op
Client.getUser:getUser·p0.90          sample          4.996           ms/op
Client.getUser:getUser·p0.95          sample          6.726           ms/op
Client.getUser:getUser·p0.99          sample         13.148           ms/op
Client.getUser:getUser·p0.999         sample         27.992           ms/op
Client.getUser:getUser·p0.9999        sample         29.753           ms/op
Client.getUser:getUser·p1.00          sample         29.753           ms/op
Client.listUser                       sample   2066  15.615 ± 0.359   ms/op
Client.listUser:listUser·p0.00        sample          5.693           ms/op
Client.listUser:listUser·p0.50        sample         14.557           ms/op
Client.listUser:listUser·p0.90        sample         21.407           ms/op
Client.listUser:listUser·p0.95        sample         25.461           ms/op
Client.listUser:listUser·p0.99        sample         35.586           ms/op
Client.listUser:listUser·p0.999       sample         41.143           ms/op
Client.listUser:listUser·p0.9999      sample         41.484           ms/op
Client.listUser:listUser·p1.00        sample         41.484           ms/op
