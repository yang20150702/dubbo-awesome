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
# Warmup Iteration   1: 1.066 ops/ms
Iteration   1: 2.680 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.680 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ops/ms
Iteration   1: 6.424 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.424 ops/ms


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
# Warmup Iteration   1: 2.250 ops/ms
Iteration   1: 5.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.324 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.902 ops/ms
Iteration   1: 1.650 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.650 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 14.427 ±(99.9%) 0.238 ms/op
Iteration   1: 6.892 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.892 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.597 ±(99.9%) 0.078 ms/op
Iteration   1: 3.800 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.800 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.705 ±(99.9%) 0.165 ms/op
Iteration   1: 5.037 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.037 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 24.589 ±(99.9%) 0.488 ms/op
Iteration   1: 16.439 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.439 ms/op


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
# Warmup Iteration   1: 10.938 ±(99.9%) 0.338 ms/op
Iteration   1: 5.986 ±(99.9%) 0.115 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.816 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   10.125 ms/op
                 createUser·p0.99:   18.743 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 22.807 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5499
  mean =      5.986 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 2142 
    [ 5.000,  7.500) = 3002 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =     10.125 ms/op
     p(99.0000) =     18.743 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 6.245 ±(99.9%) 0.235 ms/op
Iteration   1: 4.718 ±(99.9%) 0.305 ms/op
                 existUser·p0.00:   0.358 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.663 ms/op
                 existUser·p0.99:   12.881 ms/op
                 existUser·p0.999:  128.610 ms/op
                 existUser·p0.9999: 144.179 ms/op
                 existUser·p1.00:   144.179 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6777
  mean =      4.718 ±(99.9%) 0.305 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 6686 
    [ 12.500,  25.000) = 38 
    [ 25.000,  37.500) = 6 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 7 
    [ 62.500,  75.000) = 9 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 6 
    [112.500, 125.000) = 4 
    [125.000, 137.500) = 6 
    [137.500, 150.000) = 2 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.663 ms/op
     p(99.0000) =     12.881 ms/op
     p(99.9000) =    128.610 ms/op
     p(99.9900) =    144.179 ms/op
     p(99.9990) =    144.179 ms/op
     p(99.9999) =    144.179 ms/op
    p(100.0000) =    144.179 ms/op


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
# Warmup Iteration   1: 9.729 ±(99.9%) 0.346 ms/op
Iteration   1: 5.026 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.048 ms/op
                 getUser·p0.99:   12.590 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 16.335 ms/op
                 getUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6353
  mean =      5.026 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 33 
    [ 2.500,  3.750) = 410 
    [ 3.750,  5.000) = 2148 
    [ 5.000,  6.250) = 3511 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.048 ms/op
     p(99.0000) =     12.590 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 24.389 ±(99.9%) 0.624 ms/op
Iteration   1: 15.386 ±(99.9%) 0.246 ms/op
                 listUser·p0.00:   8.880 ms/op
                 listUser·p0.50:   14.655 ms/op
                 listUser·p0.90:   19.923 ms/op
                 listUser·p0.95:   23.234 ms/op
                 listUser·p0.99:   28.148 ms/op
                 listUser·p0.999:  32.835 ms/op
                 listUser·p0.9999: 32.932 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2078
  mean =     15.386 ±(99.9%) 0.246 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 1157 
    [15.000, 17.500) = 411 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      8.880 ms/op
     p(50.0000) =     14.655 ms/op
     p(90.0000) =     19.923 ms/op
     p(95.0000) =     23.234 ms/op
     p(99.0000) =     28.148 ms/op
     p(99.9000) =     32.835 ms/op
     p(99.9900) =     32.932 ms/op
     p(99.9990) =     32.932 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          2.680          ops/ms
Client.existUser                       thrpt          6.424          ops/ms
Client.getUser                         thrpt          5.324          ops/ms
Client.listUser                        thrpt          1.650          ops/ms
Client.createUser                       avgt          6.892           ms/op
Client.existUser                        avgt          3.800           ms/op
Client.getUser                          avgt          5.037           ms/op
Client.listUser                         avgt         16.439           ms/op
Client.createUser                     sample  5499    5.986 ± 0.115   ms/op
Client.createUser:createUser·p0.00    sample          2.314           ms/op
Client.createUser:createUser·p0.50    sample          5.816           ms/op
Client.createUser:createUser·p0.90    sample          6.889           ms/op
Client.createUser:createUser·p0.95    sample         10.125           ms/op
Client.createUser:createUser·p0.99    sample         18.743           ms/op
Client.createUser:createUser·p0.999   sample         22.807           ms/op
Client.createUser:createUser·p0.9999  sample         22.807           ms/op
Client.createUser:createUser·p1.00    sample         22.807           ms/op
Client.existUser                      sample  6777    4.718 ± 0.305   ms/op
Client.existUser:existUser·p0.00      sample          0.358           ms/op
Client.existUser:existUser·p0.50      sample          4.162           ms/op
Client.existUser:existUser·p0.90      sample          4.538           ms/op
Client.existUser:existUser·p0.95      sample          4.663           ms/op
Client.existUser:existUser·p0.99      sample         12.881           ms/op
Client.existUser:existUser·p0.999     sample        128.610           ms/op
Client.existUser:existUser·p0.9999    sample        144.179           ms/op
Client.existUser:existUser·p1.00      sample        144.179           ms/op
Client.getUser                        sample  6353    5.026 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          1.368           ms/op
Client.getUser:getUser·p0.50          sample          5.104           ms/op
Client.getUser:getUser·p0.90          sample          5.628           ms/op
Client.getUser:getUser·p0.95          sample          6.048           ms/op
Client.getUser:getUser·p0.99          sample         12.590           ms/op
Client.getUser:getUser·p0.999         sample         15.647           ms/op
Client.getUser:getUser·p0.9999        sample         16.335           ms/op
Client.getUser:getUser·p1.00          sample         16.335           ms/op
Client.listUser                       sample  2078   15.386 ± 0.246   ms/op
Client.listUser:listUser·p0.00        sample          8.880           ms/op
Client.listUser:listUser·p0.50        sample         14.655           ms/op
Client.listUser:listUser·p0.90        sample         19.923           ms/op
Client.listUser:listUser·p0.95        sample         23.234           ms/op
Client.listUser:listUser·p0.99        sample         28.148           ms/op
Client.listUser:listUser·p0.999       sample         32.835           ms/op
Client.listUser:listUser·p0.9999      sample         32.932           ms/op
Client.listUser:listUser·p1.00        sample         32.932           ms/op
