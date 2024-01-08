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
# Warmup Iteration   1: 2.585 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.072 ops/ms


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
# Warmup Iteration   1: 6.415 ops/ms
Iteration   1: 13.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.671 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.394 ops/ms
Iteration   1: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.241 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.219 ops/ms
Iteration   1: 3.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.380 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ±(99.9%) 0.113 ms/op
Iteration   1: 3.094 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.094 ms/op


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
# Warmup Iteration   1: 3.259 ±(99.9%) 0.030 ms/op
Iteration   1: 1.905 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.905 ms/op


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.047 ms/op
Iteration   1: 3.149 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.149 ms/op


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
# Warmup Iteration   1: 12.114 ±(99.9%) 0.212 ms/op
Iteration   1: 8.138 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.138 ms/op


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
# Warmup Iteration   1: 5.484 ±(99.9%) 0.119 ms/op
Iteration   1: 3.112 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  18.601 ms/op
                 createUser·p0.9999: 19.314 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10337
  mean =      3.112 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 1005 
    [ 2.500,  3.750) = 8530 
    [ 3.750,  5.000) = 552 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     18.601 ms/op
     p(99.9900) =     19.314 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.083 ms/op
Iteration   1: 1.792 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.064 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.299 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17841
  mean =      1.792 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 607 
    [ 1.250,  2.500) = 16420 
    [ 2.500,  3.750) = 712 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.064 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.299 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.180 ms/op
Iteration   1: 2.945 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   2.855 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  6.062 ms/op
                 getUser·p0.9999: 6.683 ms/op
                 getUser·p1.00:   6.701 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10857
  mean =      2.945 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 230 
    [2.000, 2.500) = 2051 
    [2.500, 3.000) = 4191 
    [3.000, 3.500) = 2898 
    [3.500, 4.000) = 883 
    [4.000, 4.500) = 337 
    [4.500, 5.000) = 130 
    [5.000, 5.500) = 68 
    [5.500, 6.000) = 43 
    [6.000, 6.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =      6.683 ms/op
     p(99.9990) =      6.701 ms/op
     p(99.9999) =      6.701 ms/op
    p(100.0000) =      6.701 ms/op


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
# Warmup Iteration   1: 13.530 ±(99.9%) 0.539 ms/op
Iteration   1: 9.140 ±(99.9%) 0.139 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   8.782 ms/op
                 listUser·p0.90:   12.534 ms/op
                 listUser·p0.95:   13.664 ms/op
                 listUser·p0.99:   16.350 ms/op
                 listUser·p0.999:  21.425 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3506
  mean =      9.140 ±(99.9%) 0.139 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 95 
    [ 5.000,  7.500) = 792 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 767 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.535 ms/op
     p(50.0000) =      8.782 ms/op
     p(90.0000) =     12.534 ms/op
     p(95.0000) =     13.664 ms/op
     p(99.0000) =     16.350 ms/op
     p(99.9000) =     21.425 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.072          ops/ms
Client.existUser                       thrpt         13.671          ops/ms
Client.getUser                         thrpt          9.241          ops/ms
Client.listUser                        thrpt          3.380          ops/ms
Client.createUser                       avgt          3.094           ms/op
Client.existUser                        avgt          1.905           ms/op
Client.getUser                          avgt          3.149           ms/op
Client.listUser                         avgt          8.138           ms/op
Client.createUser                     sample  10337   3.112 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.987           ms/op
Client.createUser:createUser·p0.50    sample          2.929           ms/op
Client.createUser:createUser·p0.90    sample          3.645           ms/op
Client.createUser:createUser·p0.95    sample          4.006           ms/op
Client.createUser:createUser·p0.99    sample          7.512           ms/op
Client.createUser:createUser·p0.999   sample         18.601           ms/op
Client.createUser:createUser·p0.9999  sample         19.314           ms/op
Client.createUser:createUser·p1.00    sample         19.333           ms/op
Client.existUser                      sample  17841   1.792 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.391           ms/op
Client.existUser:existUser·p0.50      sample          1.671           ms/op
Client.existUser:existUser·p0.90      sample          2.241           ms/op
Client.existUser:existUser·p0.95      sample          2.470           ms/op
Client.existUser:existUser·p0.99      sample          3.064           ms/op
Client.existUser:existUser·p0.999     sample         18.219           ms/op
Client.existUser:existUser·p0.9999    sample         18.299           ms/op
Client.existUser:existUser·p1.00      sample         18.350           ms/op
Client.getUser                        sample  10857   2.945 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          1.264           ms/op
Client.getUser:getUser·p0.50          sample          2.855           ms/op
Client.getUser:getUser·p0.90          sample          3.662           ms/op
Client.getUser:getUser·p0.95          sample          4.051           ms/op
Client.getUser:getUser·p0.99          sample          5.046           ms/op
Client.getUser:getUser·p0.999         sample          6.062           ms/op
Client.getUser:getUser·p0.9999        sample          6.683           ms/op
Client.getUser:getUser·p1.00          sample          6.701           ms/op
Client.listUser                       sample   3506   9.140 ± 0.139   ms/op
Client.listUser:listUser·p0.00        sample          2.535           ms/op
Client.listUser:listUser·p0.50        sample          8.782           ms/op
Client.listUser:listUser·p0.90        sample         12.534           ms/op
Client.listUser:listUser·p0.95        sample         13.664           ms/op
Client.listUser:listUser·p0.99        sample         16.350           ms/op
Client.listUser:listUser·p0.999       sample         21.425           ms/op
Client.listUser:listUser·p0.9999      sample         26.968           ms/op
Client.listUser:listUser·p1.00        sample         26.968           ms/op
