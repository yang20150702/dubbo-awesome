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
# Warmup Iteration   1: 2.285 ops/ms
Iteration   1: 5.628 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.628 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.388 ops/ms
Iteration   1: 13.571 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.571 ops/ms


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
# Warmup Iteration   1: 4.141 ops/ms
Iteration   1: 7.556 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.556 ops/ms


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
# Warmup Iteration   1: 1.952 ops/ms
Iteration   1: 3.065 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.065 ops/ms


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
# Warmup Iteration   1: 5.856 ±(99.9%) 0.073 ms/op
Iteration   1: 3.295 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.295 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.033 ms/op
Iteration   1: 1.820 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.820 ms/op


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
# Warmup Iteration   1: 4.774 ±(99.9%) 0.056 ms/op
Iteration   1: 3.284 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.284 ms/op


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
# Warmup Iteration   1: 13.511 ±(99.9%) 0.267 ms/op
Iteration   1: 8.261 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.261 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.109 ms/op
Iteration   1: 3.002 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.023 ms/op
                 createUser·p0.999:  7.079 ms/op
                 createUser·p0.9999: 9.813 ms/op
                 createUser·p1.00:   9.814 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10636
  mean =      3.002 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 35 
    [ 1.500,  2.000) = 318 
    [ 2.000,  2.500) = 1755 
    [ 2.500,  3.000) = 4413 
    [ 3.000,  3.500) = 2134 
    [ 3.500,  4.000) = 1098 
    [ 4.000,  4.500) = 474 
    [ 4.500,  5.000) = 203 
    [ 5.000,  5.500) = 73 
    [ 5.500,  6.000) = 26 
    [ 6.000,  6.500) = 43 
    [ 6.500,  7.000) = 51 
    [ 7.000,  7.500) = 4 
    [ 7.500,  8.000) = 4 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 2 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.023 ms/op
     p(99.9000) =      7.079 ms/op
     p(99.9900) =      9.813 ms/op
     p(99.9990) =      9.814 ms/op
     p(99.9999) =      9.814 ms/op
    p(100.0000) =      9.814 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.083 ms/op
Iteration   1: 1.800 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.325 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   4.082 ms/op
                 existUser·p0.999:  26.608 ms/op
                 existUser·p0.9999: 27.300 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17745
  mean =      1.800 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16935 
    [ 2.500,  5.000) = 728 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.325 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.082 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     27.300 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.116 ms/op
Iteration   1: 3.313 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.945 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 10.977 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9732
  mean =      3.313 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1473 
    [ 2.500,  3.750) = 5791 
    [ 3.750,  5.000) = 2133 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.945 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


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
# Warmup Iteration   1: 13.511 ±(99.9%) 0.452 ms/op
Iteration   1: 9.631 ±(99.9%) 0.148 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   9.306 ms/op
                 listUser·p0.90:   12.845 ms/op
                 listUser·p0.95:   14.064 ms/op
                 listUser·p0.99:   17.891 ms/op
                 listUser·p0.999:  22.069 ms/op
                 listUser·p0.9999: 25.526 ms/op
                 listUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3311
  mean =      9.631 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 49 
    [ 5.000,  7.500) = 534 
    [ 7.500, 10.000) = 1431 
    [10.000, 12.500) = 881 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      9.306 ms/op
     p(90.0000) =     12.845 ms/op
     p(95.0000) =     14.064 ms/op
     p(99.0000) =     17.891 ms/op
     p(99.9000) =     22.069 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.628          ops/ms
Client.existUser                       thrpt         13.571          ops/ms
Client.getUser                         thrpt          7.556          ops/ms
Client.listUser                        thrpt          3.065          ops/ms
Client.createUser                       avgt          3.295           ms/op
Client.existUser                        avgt          1.820           ms/op
Client.getUser                          avgt          3.284           ms/op
Client.listUser                         avgt          8.261           ms/op
Client.createUser                     sample  10636   3.002 ± 0.024   ms/op
Client.createUser:createUser·p0.00    sample          1.035           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.875           ms/op
Client.createUser:createUser·p0.95    sample          4.358           ms/op
Client.createUser:createUser·p0.99    sample          6.023           ms/op
Client.createUser:createUser·p0.999   sample          7.079           ms/op
Client.createUser:createUser·p0.9999  sample          9.813           ms/op
Client.createUser:createUser·p1.00    sample          9.814           ms/op
Client.existUser                      sample  17745   1.800 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.325           ms/op
Client.existUser:existUser·p0.50      sample          1.663           ms/op
Client.existUser:existUser·p0.90      sample          2.261           ms/op
Client.existUser:existUser·p0.95      sample          2.470           ms/op
Client.existUser:existUser·p0.99      sample          4.082           ms/op
Client.existUser:existUser·p0.999     sample         26.608           ms/op
Client.existUser:existUser·p0.9999    sample         27.300           ms/op
Client.existUser:existUser·p1.00      sample         27.427           ms/op
Client.getUser                        sample   9732   3.313 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.566           ms/op
Client.getUser:getUser·p0.50          sample          3.199           ms/op
Client.getUser:getUser·p0.90          sample          4.252           ms/op
Client.getUser:getUser·p0.95          sample          4.637           ms/op
Client.getUser:getUser·p0.99          sample          5.945           ms/op
Client.getUser:getUser·p0.999         sample         10.633           ms/op
Client.getUser:getUser·p0.9999        sample         10.977           ms/op
Client.getUser:getUser·p1.00          sample         10.977           ms/op
Client.listUser                       sample   3311   9.631 ± 0.148   ms/op
Client.listUser:listUser·p0.00        sample          1.229           ms/op
Client.listUser:listUser·p0.50        sample          9.306           ms/op
Client.listUser:listUser·p0.90        sample         12.845           ms/op
Client.listUser:listUser·p0.95        sample         14.064           ms/op
Client.listUser:listUser·p0.99        sample         17.891           ms/op
Client.listUser:listUser·p0.999       sample         22.069           ms/op
Client.listUser:listUser·p0.9999      sample         25.526           ms/op
Client.listUser:listUser·p1.00        sample         25.526           ms/op
