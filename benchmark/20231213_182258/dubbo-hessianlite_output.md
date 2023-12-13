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
# Warmup Iteration   1: 2.045 ops/ms
Iteration   1: 5.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.973 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.730 ops/ms
Iteration   1: 13.441 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.441 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ops/ms
Iteration   1: 8.094 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.094 ops/ms


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
# Warmup Iteration   1: 2.169 ops/ms
Iteration   1: 3.687 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.687 ops/ms


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
# Warmup Iteration   1: 6.003 ±(99.9%) 0.112 ms/op
Iteration   1: 3.081 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.081 ms/op


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
# Warmup Iteration   1: 2.941 ±(99.9%) 0.028 ms/op
Iteration   1: 2.025 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.025 ms/op


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
# Warmup Iteration   1: 5.219 ±(99.9%) 0.061 ms/op
Iteration   1: 3.008 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.008 ms/op


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
# Warmup Iteration   1: 11.813 ±(99.9%) 0.203 ms/op
Iteration   1: 8.064 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.064 ms/op


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
# Warmup Iteration   1: 5.523 ±(99.9%) 0.131 ms/op
Iteration   1: 2.979 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.114 ms/op
                 createUser·p0.99:   8.122 ms/op
                 createUser·p0.999:  12.128 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10752
  mean =      2.979 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2391 
    [ 2.500,  3.750) = 7448 
    [ 3.750,  5.000) = 667 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.114 ms/op
     p(99.0000) =      8.122 ms/op
     p(99.9000) =     12.128 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ±(99.9%) 0.078 ms/op
Iteration   1: 1.814 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.195 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   4.209 ms/op
                 existUser·p0.999:  21.037 ms/op
                 existUser·p0.9999: 22.208 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17822
  mean =      1.814 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17252 
    [ 2.500,  5.000) = 434 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      4.209 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     22.208 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.145 ms/op
Iteration   1: 3.100 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.396 ms/op
                 getUser·p0.999:  14.434 ms/op
                 getUser·p0.9999: 15.030 ms/op
                 getUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10313
  mean =      3.100 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 2261 
    [ 2.500,  3.750) = 6556 
    [ 3.750,  5.000) = 1278 
    [ 5.000,  6.250) = 151 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.396 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     15.030 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 11.687 ±(99.9%) 0.431 ms/op
Iteration   1: 8.212 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   7.840 ms/op
                 listUser·p0.90:   10.990 ms/op
                 listUser·p0.95:   12.272 ms/op
                 listUser·p0.99:   16.226 ms/op
                 listUser·p0.999:  18.003 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3881
  mean =      8.212 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 122 
    [ 5.000,  7.500) = 1482 
    [ 7.500, 10.000) = 1610 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      7.840 ms/op
     p(90.0000) =     10.990 ms/op
     p(95.0000) =     12.272 ms/op
     p(99.0000) =     16.226 ms/op
     p(99.9000) =     18.003 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.973          ops/ms
Client.existUser                       thrpt         13.441          ops/ms
Client.getUser                         thrpt          8.094          ops/ms
Client.listUser                        thrpt          3.687          ops/ms
Client.createUser                       avgt          3.081           ms/op
Client.existUser                        avgt          2.025           ms/op
Client.getUser                          avgt          3.008           ms/op
Client.listUser                         avgt          8.064           ms/op
Client.createUser                     sample  10752   2.979 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          0.919           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.629           ms/op
Client.createUser:createUser·p0.95    sample          4.114           ms/op
Client.createUser:createUser·p0.99    sample          8.122           ms/op
Client.createUser:createUser·p0.999   sample         12.128           ms/op
Client.createUser:createUser·p0.9999  sample         17.760           ms/op
Client.createUser:createUser·p1.00    sample         17.760           ms/op
Client.existUser                      sample  17822   1.814 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.589           ms/op
Client.existUser:existUser·p0.50      sample          1.665           ms/op
Client.existUser:existUser·p0.90      sample          2.195           ms/op
Client.existUser:existUser·p0.95      sample          2.343           ms/op
Client.existUser:existUser·p0.99      sample          4.209           ms/op
Client.existUser:existUser·p0.999     sample         21.037           ms/op
Client.existUser:existUser·p0.9999    sample         22.208           ms/op
Client.existUser:existUser·p1.00      sample         22.413           ms/op
Client.getUser                        sample  10313   3.100 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.942           ms/op
Client.getUser:getUser·p0.50          sample          2.978           ms/op
Client.getUser:getUser·p0.90          sample          3.932           ms/op
Client.getUser:getUser·p0.95          sample          4.391           ms/op
Client.getUser:getUser·p0.99          sample          5.396           ms/op
Client.getUser:getUser·p0.999         sample         14.434           ms/op
Client.getUser:getUser·p0.9999        sample         15.030           ms/op
Client.getUser:getUser·p1.00          sample         15.041           ms/op
Client.listUser                       sample   3881   8.212 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          1.276           ms/op
Client.listUser:listUser·p0.50        sample          7.840           ms/op
Client.listUser:listUser·p0.90        sample         10.990           ms/op
Client.listUser:listUser·p0.95        sample         12.272           ms/op
Client.listUser:listUser·p0.99        sample         16.226           ms/op
Client.listUser:listUser·p0.999       sample         18.003           ms/op
Client.listUser:listUser·p0.9999      sample         23.593           ms/op
Client.listUser:listUser·p1.00        sample         23.593           ms/op
