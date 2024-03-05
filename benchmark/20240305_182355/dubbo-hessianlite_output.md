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
# Warmup Iteration   1: 2.066 ops/ms
Iteration   1: 5.505 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.505 ops/ms


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
# Warmup Iteration   1: 5.428 ops/ms
Iteration   1: 11.517 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.517 ops/ms


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
# Warmup Iteration   1: 3.653 ops/ms
Iteration   1: 8.210 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.210 ops/ms


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
# Warmup Iteration   1: 2.294 ops/ms
Iteration   1: 3.746 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.746 ops/ms


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.055 ms/op
Iteration   1: 3.235 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.235 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.036 ms/op
Iteration   1: 1.859 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.070 ms/op
Iteration   1: 3.342 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.342 ms/op


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
# Warmup Iteration   1: 12.688 ±(99.9%) 0.282 ms/op
Iteration   1: 8.768 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.768 ms/op


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.118 ms/op
Iteration   1: 2.900 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.021 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11025
  mean =      2.900 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 4382 
    [ 2.500,  3.750) = 5628 
    [ 3.750,  5.000) = 764 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.021 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 3.135 ±(99.9%) 0.085 ms/op
Iteration   1: 2.077 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   2.050 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.579 ms/op
                 existUser·p0.9999: 6.115 ms/op
                 existUser·p1.00:   6.455 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15396
  mean =      2.077 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 2 
    [0.500, 1.000) = 34 
    [1.000, 1.500) = 1616 
    [1.500, 2.000) = 5445 
    [2.000, 2.500) = 5780 
    [2.500, 3.000) = 2139 
    [3.000, 3.500) = 182 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 55 
    [4.500, 5.000) = 17 
    [5.000, 5.500) = 57 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      5.579 ms/op
     p(99.9900) =      6.115 ms/op
     p(99.9990) =      6.455 ms/op
     p(99.9999) =      6.455 ms/op
    p(100.0000) =      6.455 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.104 ms/op
Iteration   1: 3.347 ±(99.9%) 0.048 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  21.922 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9565
  mean =      3.347 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1683 
    [ 2.500,  5.000) = 7581 
    [ 5.000,  7.500) = 233 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 13.588 ±(99.9%) 0.423 ms/op
Iteration   1: 9.291 ±(99.9%) 0.148 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   8.880 ms/op
                 listUser·p0.90:   12.812 ms/op
                 listUser·p0.95:   14.095 ms/op
                 listUser·p0.99:   17.126 ms/op
                 listUser·p0.999:  24.342 ms/op
                 listUser·p0.9999: 32.014 ms/op
                 listUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3436
  mean =      9.291 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 70 
    [ 5.000,  7.500) = 758 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 718 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      8.880 ms/op
     p(90.0000) =     12.812 ms/op
     p(95.0000) =     14.095 ms/op
     p(99.0000) =     17.126 ms/op
     p(99.9000) =     24.342 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.505          ops/ms
Client.existUser                       thrpt         11.517          ops/ms
Client.getUser                         thrpt          8.210          ops/ms
Client.listUser                        thrpt          3.746          ops/ms
Client.createUser                       avgt          3.235           ms/op
Client.existUser                        avgt          1.859           ms/op
Client.getUser                          avgt          3.342           ms/op
Client.listUser                         avgt          8.768           ms/op
Client.createUser                     sample  11025   2.900 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          0.630           ms/op
Client.createUser:createUser·p0.50    sample          2.695           ms/op
Client.createUser:createUser·p0.90    sample          3.707           ms/op
Client.createUser:createUser·p0.95    sample          4.021           ms/op
Client.createUser:createUser·p0.99    sample          7.971           ms/op
Client.createUser:createUser·p0.999   sample         13.484           ms/op
Client.createUser:createUser·p0.9999  sample         13.500           ms/op
Client.createUser:createUser·p1.00    sample         13.500           ms/op
Client.existUser                      sample  15396   2.077 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.490           ms/op
Client.existUser:existUser·p0.50      sample          2.050           ms/op
Client.existUser:existUser·p0.90      sample          2.646           ms/op
Client.existUser:existUser·p0.95      sample          2.822           ms/op
Client.existUser:existUser·p0.99      sample          4.051           ms/op
Client.existUser:existUser·p0.999     sample          5.579           ms/op
Client.existUser:existUser·p0.9999    sample          6.115           ms/op
Client.existUser:existUser·p1.00      sample          6.455           ms/op
Client.getUser                        sample   9565   3.347 ± 0.048   ms/op
Client.getUser:getUser·p0.00          sample          0.667           ms/op
Client.getUser:getUser·p0.50          sample          3.224           ms/op
Client.getUser:getUser·p0.90          sample          4.121           ms/op
Client.getUser:getUser·p0.95          sample          4.489           ms/op
Client.getUser:getUser·p0.99          sample          6.201           ms/op
Client.getUser:getUser·p0.999         sample         21.922           ms/op
Client.getUser:getUser·p0.9999        sample         23.396           ms/op
Client.getUser:getUser·p1.00          sample         23.396           ms/op
Client.listUser                       sample   3436   9.291 ± 0.148   ms/op
Client.listUser:listUser·p0.00        sample          2.249           ms/op
Client.listUser:listUser·p0.50        sample          8.880           ms/op
Client.listUser:listUser·p0.90        sample         12.812           ms/op
Client.listUser:listUser·p0.95        sample         14.095           ms/op
Client.listUser:listUser·p0.99        sample         17.126           ms/op
Client.listUser:listUser·p0.999       sample         24.342           ms/op
Client.listUser:listUser·p0.9999      sample         32.014           ms/op
Client.listUser:listUser·p1.00        sample         32.014           ms/op
