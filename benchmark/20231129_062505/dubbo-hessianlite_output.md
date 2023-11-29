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
# Warmup Iteration   1: 2.087 ops/ms
Iteration   1: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.128 ops/ms


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
# Warmup Iteration   1: 7.444 ops/ms
Iteration   1: 12.209 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.209 ops/ms


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
# Warmup Iteration   1: 4.671 ops/ms
Iteration   1: 8.989 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.989 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.088 ops/ms
Iteration   1: 3.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.355 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.058 ms/op
Iteration   1: 3.035 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.035 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ±(99.9%) 0.030 ms/op
Iteration   1: 1.844 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.844 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.056 ms/op
Iteration   1: 2.806 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.806 ms/op


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
# Warmup Iteration   1: 11.933 ±(99.9%) 0.272 ms/op
Iteration   1: 8.172 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.172 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.075 ms/op
Iteration   1: 3.073 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.427 ms/op
                 createUser·p0.999:  24.622 ms/op
                 createUser·p0.9999: 24.967 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10594
  mean =      3.073 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2702 
    [ 2.500,  5.000) = 7619 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.427 ms/op
     p(99.9000) =     24.622 ms/op
     p(99.9900) =     24.967 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 2.874 ±(99.9%) 0.057 ms/op
Iteration   1: 2.149 ±(99.9%) 0.092 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.879 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  67.257 ms/op
                 existUser·p0.9999: 67.902 ms/op
                 existUser·p1.00:   68.157 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14868
  mean =      2.149 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14722 
    [ 5.000, 10.000) = 50 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     67.257 ms/op
     p(99.9900) =     67.902 ms/op
     p(99.9990) =     68.157 ms/op
     p(99.9999) =     68.157 ms/op
    p(100.0000) =     68.157 ms/op


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.089 ms/op
Iteration   1: 3.017 ±(99.9%) 0.073 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.814 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.098 ms/op
                 getUser·p0.99:   5.787 ms/op
                 getUser·p0.999:  42.034 ms/op
                 getUser·p0.9999: 43.516 ms/op
                 getUser·p1.00:   43.516 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10651
  mean =      3.017 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10421 
    [ 5.000, 10.000) = 163 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.098 ms/op
     p(99.0000) =      5.787 ms/op
     p(99.9000) =     42.034 ms/op
     p(99.9900) =     43.516 ms/op
     p(99.9990) =     43.516 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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
# Warmup Iteration   1: 11.751 ±(99.9%) 0.367 ms/op
Iteration   1: 8.065 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   7.717 ms/op
                 listUser·p0.90:   11.026 ms/op
                 listUser·p0.95:   11.960 ms/op
                 listUser·p0.99:   14.336 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3999
  mean =      8.065 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 32 
    [ 3.750,  5.000) = 170 
    [ 5.000,  6.250) = 497 
    [ 6.250,  7.500) = 1123 
    [ 7.500,  8.750) = 888 
    [ 8.750, 10.000) = 559 
    [10.000, 11.250) = 378 
    [11.250, 12.500) = 237 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      7.717 ms/op
     p(90.0000) =     11.026 ms/op
     p(95.0000) =     11.960 ms/op
     p(99.0000) =     14.336 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.128          ops/ms
Client.existUser                       thrpt         12.209          ops/ms
Client.getUser                         thrpt          8.989          ops/ms
Client.listUser                        thrpt          3.355          ops/ms
Client.createUser                       avgt          3.035           ms/op
Client.existUser                        avgt          1.844           ms/op
Client.getUser                          avgt          2.806           ms/op
Client.listUser                         avgt          8.172           ms/op
Client.createUser                     sample  10594   3.073 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.335           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.895           ms/op
Client.createUser:createUser·p0.95    sample          4.514           ms/op
Client.createUser:createUser·p0.99    sample          6.427           ms/op
Client.createUser:createUser·p0.999   sample         24.622           ms/op
Client.createUser:createUser·p0.9999  sample         24.967           ms/op
Client.createUser:createUser·p1.00    sample         24.969           ms/op
Client.existUser                      sample  14868   2.149 ± 0.092   ms/op
Client.existUser:existUser·p0.00      sample          0.575           ms/op
Client.existUser:existUser·p0.50      sample          1.886           ms/op
Client.existUser:existUser·p0.90      sample          2.560           ms/op
Client.existUser:existUser·p0.95      sample          2.879           ms/op
Client.existUser:existUser·p0.99      sample          4.792           ms/op
Client.existUser:existUser·p0.999     sample         67.257           ms/op
Client.existUser:existUser·p0.9999    sample         67.902           ms/op
Client.existUser:existUser·p1.00      sample         68.157           ms/op
Client.getUser                        sample  10651   3.017 ± 0.073   ms/op
Client.getUser:getUser·p0.00          sample          0.823           ms/op
Client.getUser:getUser·p0.50          sample          2.814           ms/op
Client.getUser:getUser·p0.90          sample          3.637           ms/op
Client.getUser:getUser·p0.95          sample          4.098           ms/op
Client.getUser:getUser·p0.99          sample          5.787           ms/op
Client.getUser:getUser·p0.999         sample         42.034           ms/op
Client.getUser:getUser·p0.9999        sample         43.516           ms/op
Client.getUser:getUser·p1.00          sample         43.516           ms/op
Client.listUser                       sample   3999   8.065 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          1.659           ms/op
Client.listUser:listUser·p0.50        sample          7.717           ms/op
Client.listUser:listUser·p0.90        sample         11.026           ms/op
Client.listUser:listUser·p0.95        sample         11.960           ms/op
Client.listUser:listUser·p0.99        sample         14.336           ms/op
Client.listUser:listUser·p0.999       sample         17.695           ms/op
Client.listUser:listUser·p0.9999      sample         18.547           ms/op
Client.listUser:listUser·p1.00        sample         18.547           ms/op
