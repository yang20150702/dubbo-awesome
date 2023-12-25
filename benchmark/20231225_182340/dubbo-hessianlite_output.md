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
# Warmup Iteration   1: 2.320 ops/ms
Iteration   1: 6.310 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.310 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.575 ops/ms
Iteration   1: 12.232 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.232 ops/ms


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
# Warmup Iteration   1: 4.304 ops/ms
Iteration   1: 8.663 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.663 ops/ms


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
# Warmup Iteration   1: 2.247 ops/ms
Iteration   1: 3.356 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.356 ops/ms


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
# Warmup Iteration   1: 5.546 ±(99.9%) 0.079 ms/op
Iteration   1: 3.047 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.047 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.027 ms/op
Iteration   1: 1.803 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.803 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.054 ms/op
Iteration   1: 3.268 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.268 ms/op


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
# Warmup Iteration   1: 12.970 ±(99.9%) 0.338 ms/op
Iteration   1: 9.408 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.408 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.104 ms/op
Iteration   1: 2.851 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   4.007 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  13.871 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11353
  mean =      2.851 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2943 
    [ 2.500,  3.750) = 7773 
    [ 3.750,  5.000) = 520 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      4.007 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     13.871 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.089 ms/op
Iteration   1: 2.053 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.261 ms/op
                 existUser·p0.50:   1.939 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.929 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 18.637 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15577
  mean =      2.053 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 610 
    [ 1.250,  2.500) = 12945 
    [ 2.500,  3.750) = 1764 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     18.637 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.122 ms/op
Iteration   1: 3.140 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  7.272 ms/op
                 getUser·p0.9999: 8.906 ms/op
                 getUser·p1.00:   8.913 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10282
  mean =      3.140 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 68 
    [1.500, 2.000) = 264 
    [2.000, 2.500) = 1770 
    [2.500, 3.000) = 2370 
    [3.000, 3.500) = 3220 
    [3.500, 4.000) = 1687 
    [4.000, 4.500) = 443 
    [4.500, 5.000) = 182 
    [5.000, 5.500) = 101 
    [5.500, 6.000) = 46 
    [6.000, 6.500) = 77 
    [6.500, 7.000) = 25 
    [7.000, 7.500) = 22 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =      7.272 ms/op
     p(99.9900) =      8.906 ms/op
     p(99.9990) =      8.913 ms/op
     p(99.9999) =      8.913 ms/op
    p(100.0000) =      8.913 ms/op


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
# Warmup Iteration   1: 12.408 ±(99.9%) 0.432 ms/op
Iteration   1: 8.312 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   7.954 ms/op
                 listUser·p0.90:   10.977 ms/op
                 listUser·p0.95:   12.288 ms/op
                 listUser·p0.99:   16.068 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 26.083 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3845
  mean =      8.312 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 109 
    [ 5.000,  7.500) = 1401 
    [ 7.500, 10.000) = 1661 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.092 ms/op
     p(50.0000) =      7.954 ms/op
     p(90.0000) =     10.977 ms/op
     p(95.0000) =     12.288 ms/op
     p(99.0000) =     16.068 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.310          ops/ms
Client.existUser                       thrpt         12.232          ops/ms
Client.getUser                         thrpt          8.663          ops/ms
Client.listUser                        thrpt          3.356          ops/ms
Client.createUser                       avgt          3.047           ms/op
Client.existUser                        avgt          1.803           ms/op
Client.getUser                          avgt          3.268           ms/op
Client.listUser                         avgt          9.408           ms/op
Client.createUser                     sample  11353   2.851 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.182           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.375           ms/op
Client.createUser:createUser·p0.95    sample          4.007           ms/op
Client.createUser:createUser·p0.99    sample          5.005           ms/op
Client.createUser:createUser·p0.999   sample         13.871           ms/op
Client.createUser:createUser·p0.9999  sample         14.156           ms/op
Client.createUser:createUser·p1.00    sample         14.156           ms/op
Client.existUser                      sample  15577   2.053 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.261           ms/op
Client.existUser:existUser·p0.50      sample          1.939           ms/op
Client.existUser:existUser·p0.90      sample          2.585           ms/op
Client.existUser:existUser·p0.95      sample          2.929           ms/op
Client.existUser:existUser·p0.99      sample          4.571           ms/op
Client.existUser:existUser·p0.999     sample         12.272           ms/op
Client.existUser:existUser·p0.9999    sample         18.637           ms/op
Client.existUser:existUser·p1.00      sample         18.711           ms/op
Client.getUser                        sample  10282   3.140 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.860           ms/op
Client.getUser:getUser·p0.50          sample          3.097           ms/op
Client.getUser:getUser·p0.90          sample          3.949           ms/op
Client.getUser:getUser·p0.95          sample          4.399           ms/op
Client.getUser:getUser·p0.99          sample          6.193           ms/op
Client.getUser:getUser·p0.999         sample          7.272           ms/op
Client.getUser:getUser·p0.9999        sample          8.906           ms/op
Client.getUser:getUser·p1.00          sample          8.913           ms/op
Client.listUser                       sample   3845   8.312 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          3.092           ms/op
Client.listUser:listUser·p0.50        sample          7.954           ms/op
Client.listUser:listUser·p0.90        sample         10.977           ms/op
Client.listUser:listUser·p0.95        sample         12.288           ms/op
Client.listUser:listUser·p0.99        sample         16.068           ms/op
Client.listUser:listUser·p0.999       sample         22.086           ms/op
Client.listUser:listUser·p0.9999      sample         26.083           ms/op
Client.listUser:listUser·p1.00        sample         26.083           ms/op
