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
# Warmup Iteration   1: 2.166 ops/ms
Iteration   1: 5.656 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.656 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ops/ms
Iteration   1: 12.754 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.754 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ops/ms
Iteration   1: 8.737 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.737 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.251 ops/ms
Iteration   1: 4.116 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.116 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.271 ±(99.9%) 0.064 ms/op
Iteration   1: 3.013 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.013 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.073 ±(99.9%) 0.037 ms/op
Iteration   1: 1.769 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.769 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.633 ±(99.9%) 0.051 ms/op
Iteration   1: 3.246 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.246 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.634 ±(99.9%) 0.184 ms/op
Iteration   1: 8.220 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.220 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.148 ±(99.9%) 0.144 ms/op
Iteration   1: 2.992 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  13.613 ms/op
                 createUser·p0.9999: 14.121 ms/op
                 createUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10686
  mean =      2.992 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 3323 
    [ 2.500,  3.750) = 6375 
    [ 3.750,  5.000) = 726 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     13.613 ms/op
     p(99.9900) =     14.121 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ±(99.9%) 0.078 ms/op
Iteration   1: 1.740 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 6.958 ms/op
                 existUser·p1.00:   7.062 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18413
  mean =      1.740 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 302 
    [1.000, 1.500) = 4732 
    [1.500, 2.000) = 9705 
    [2.000, 2.500) = 2871 
    [2.500, 3.000) = 505 
    [3.000, 3.500) = 110 
    [3.500, 4.000) = 31 
    [4.000, 4.500) = 40 
    [4.500, 5.000) = 67 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 28 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =      6.958 ms/op
     p(99.9990) =      7.062 ms/op
     p(99.9999) =      7.062 ms/op
    p(100.0000) =      7.062 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ±(99.9%) 0.097 ms/op
Iteration   1: 3.113 ±(99.9%) 0.105 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.826 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.992 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  64.501 ms/op
                 getUser·p0.9999: 69.858 ms/op
                 getUser·p1.00:   69.861 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10265
  mean =      3.113 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10116 
    [ 5.000, 10.000) = 96 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.992 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     64.501 ms/op
     p(99.9900) =     69.858 ms/op
     p(99.9990) =     69.861 ms/op
     p(99.9999) =     69.861 ms/op
    p(100.0000) =     69.861 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.580 ±(99.9%) 0.426 ms/op
Iteration   1: 8.164 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   7.807 ms/op
                 listUser·p0.90:   10.877 ms/op
                 listUser·p0.95:   11.944 ms/op
                 listUser·p0.99:   15.886 ms/op
                 listUser·p0.999:  20.057 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3920
  mean =      8.164 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 97 
    [ 5.000,  7.500) = 1550 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      7.807 ms/op
     p(90.0000) =     10.877 ms/op
     p(95.0000) =     11.944 ms/op
     p(99.0000) =     15.886 ms/op
     p(99.9000) =     20.057 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.656          ops/ms
Client.existUser                       thrpt         12.754          ops/ms
Client.getUser                         thrpt          8.737          ops/ms
Client.listUser                        thrpt          4.116          ops/ms
Client.createUser                       avgt          3.013           ms/op
Client.existUser                        avgt          1.769           ms/op
Client.getUser                          avgt          3.246           ms/op
Client.listUser                         avgt          8.220           ms/op
Client.createUser                     sample  10686   2.992 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.707           ms/op
Client.createUser:createUser·p0.95    sample          4.088           ms/op
Client.createUser:createUser·p0.99    sample          8.733           ms/op
Client.createUser:createUser·p0.999   sample         13.613           ms/op
Client.createUser:createUser·p0.9999  sample         14.121           ms/op
Client.createUser:createUser·p1.00    sample         14.123           ms/op
Client.existUser                      sample  18413   1.740 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.541           ms/op
Client.existUser:existUser·p0.50      sample          1.710           ms/op
Client.existUser:existUser·p0.90      sample          2.167           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          3.551           ms/op
Client.existUser:existUser·p0.999     sample          6.750           ms/op
Client.existUser:existUser·p0.9999    sample          6.958           ms/op
Client.existUser:existUser·p1.00      sample          7.062           ms/op
Client.getUser                        sample  10265   3.113 ± 0.105   ms/op
Client.getUser:getUser·p0.00          sample          1.073           ms/op
Client.getUser:getUser·p0.50          sample          2.826           ms/op
Client.getUser:getUser·p0.90          sample          3.674           ms/op
Client.getUser:getUser·p0.95          sample          3.992           ms/op
Client.getUser:getUser·p0.99          sample          5.685           ms/op
Client.getUser:getUser·p0.999         sample         64.501           ms/op
Client.getUser:getUser·p0.9999        sample         69.858           ms/op
Client.getUser:getUser·p1.00          sample         69.861           ms/op
Client.listUser                       sample   3920   8.164 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.163           ms/op
Client.listUser:listUser·p0.50        sample          7.807           ms/op
Client.listUser:listUser·p0.90        sample         10.877           ms/op
Client.listUser:listUser·p0.95        sample         11.944           ms/op
Client.listUser:listUser·p0.99        sample         15.886           ms/op
Client.listUser:listUser·p0.999       sample         20.057           ms/op
Client.listUser:listUser·p0.9999      sample         20.939           ms/op
Client.listUser:listUser·p1.00        sample         20.939           ms/op
