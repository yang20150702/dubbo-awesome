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
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 5.553 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.553 ops/ms


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
# Warmup Iteration   1: 5.676 ops/ms
Iteration   1: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.781 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ops/ms
Iteration   1: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.401 ops/ms


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
# Warmup Iteration   1: 2.190 ops/ms
Iteration   1: 3.278 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.278 ops/ms


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
# Warmup Iteration   1: 5.977 ±(99.9%) 0.084 ms/op
Iteration   1: 3.385 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.385 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.046 ms/op
Iteration   1: 1.807 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.807 ms/op


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.057 ms/op
Iteration   1: 3.026 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.026 ms/op


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
# Warmup Iteration   1: 13.951 ±(99.9%) 0.221 ms/op
Iteration   1: 7.762 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.762 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.110 ms/op
Iteration   1: 2.923 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   9.923 ms/op
                 createUser·p0.999:  15.663 ms/op
                 createUser·p0.9999: 16.285 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10933
  mean =      2.923 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2389 
    [ 2.500,  3.750) = 7704 
    [ 3.750,  5.000) = 617 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      9.923 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     16.285 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.072 ms/op
Iteration   1: 1.929 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.387 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  4.767 ms/op
                 existUser·p0.9999: 6.925 ms/op
                 existUser·p1.00:   6.930 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16564
  mean =      1.929 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 32 
    [1.000, 1.500) = 1706 
    [1.500, 2.000) = 8584 
    [2.000, 2.500) = 4953 
    [2.500, 3.000) = 1165 
    [3.000, 3.500) = 73 
    [3.500, 4.000) = 16 
    [4.000, 4.500) = 13 
    [4.500, 5.000) = 3 
    [5.000, 5.500) = 4 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =      4.767 ms/op
     p(99.9900) =      6.925 ms/op
     p(99.9990) =      6.930 ms/op
     p(99.9999) =      6.930 ms/op
    p(100.0000) =      6.930 ms/op


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.142 ms/op
Iteration   1: 2.939 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.879 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.975 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 8.007 ms/op
                 getUser·p1.00:   8.045 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10866
  mean =      2.939 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 29 
    [1.500, 2.000) = 518 
    [2.000, 2.500) = 2576 
    [2.500, 3.000) = 3039 
    [3.000, 3.500) = 2945 
    [3.500, 4.000) = 1214 
    [4.000, 4.500) = 269 
    [4.500, 5.000) = 75 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 45 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 30 
    [7.000, 7.500) = 48 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.975 ms/op
     p(99.9000) =      7.465 ms/op
     p(99.9900) =      8.007 ms/op
     p(99.9990) =      8.045 ms/op
     p(99.9999) =      8.045 ms/op
    p(100.0000) =      8.045 ms/op


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
# Warmup Iteration   1: 11.968 ±(99.9%) 0.374 ms/op
Iteration   1: 7.948 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   10.453 ms/op
                 listUser·p0.95:   11.846 ms/op
                 listUser·p0.99:   18.568 ms/op
                 listUser·p0.999:  22.015 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4033
  mean =      7.948 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 147 
    [ 5.000,  7.500) = 1861 
    [ 7.500, 10.000) = 1477 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.593 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =     10.453 ms/op
     p(95.0000) =     11.846 ms/op
     p(99.0000) =     18.568 ms/op
     p(99.9000) =     22.015 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.553          ops/ms
Client.existUser                       thrpt         12.781          ops/ms
Client.getUser                         thrpt          8.401          ops/ms
Client.listUser                        thrpt          3.278          ops/ms
Client.createUser                       avgt          3.385           ms/op
Client.existUser                        avgt          1.807           ms/op
Client.getUser                          avgt          3.026           ms/op
Client.listUser                         avgt          7.762           ms/op
Client.createUser                     sample  10933   2.923 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.061           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.510           ms/op
Client.createUser:createUser·p0.95    sample          4.076           ms/op
Client.createUser:createUser·p0.99    sample          9.923           ms/op
Client.createUser:createUser·p0.999   sample         15.663           ms/op
Client.createUser:createUser·p0.9999  sample         16.285           ms/op
Client.createUser:createUser·p1.00    sample         16.302           ms/op
Client.existUser                      sample  16564   1.929 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.387           ms/op
Client.existUser:existUser·p0.50      sample          1.884           ms/op
Client.existUser:existUser·p0.90      sample          2.445           ms/op
Client.existUser:existUser·p0.95      sample          2.601           ms/op
Client.existUser:existUser·p0.99      sample          2.949           ms/op
Client.existUser:existUser·p0.999     sample          4.767           ms/op
Client.existUser:existUser·p0.9999    sample          6.925           ms/op
Client.existUser:existUser·p1.00      sample          6.930           ms/op
Client.getUser                        sample  10866   2.939 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.024           ms/op
Client.getUser:getUser·p0.50          sample          2.879           ms/op
Client.getUser:getUser·p0.90          sample          3.682           ms/op
Client.getUser:getUser·p0.95          sample          4.002           ms/op
Client.getUser:getUser·p0.99          sample          5.975           ms/op
Client.getUser:getUser·p0.999         sample          7.465           ms/op
Client.getUser:getUser·p0.9999        sample          8.007           ms/op
Client.getUser:getUser·p1.00          sample          8.045           ms/op
Client.listUser                       sample   4033   7.948 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.593           ms/op
Client.listUser:listUser·p0.50        sample          7.504           ms/op
Client.listUser:listUser·p0.90        sample         10.453           ms/op
Client.listUser:listUser·p0.95        sample         11.846           ms/op
Client.listUser:listUser·p0.99        sample         18.568           ms/op
Client.listUser:listUser·p0.999       sample         22.015           ms/op
Client.listUser:listUser·p0.9999      sample         24.510           ms/op
Client.listUser:listUser·p1.00        sample         24.510           ms/op
