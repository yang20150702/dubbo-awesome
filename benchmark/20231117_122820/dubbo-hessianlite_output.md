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
# Warmup Iteration   1: 2.593 ops/ms
Iteration   1: 5.938 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.938 ops/ms


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
# Warmup Iteration   1: 6.210 ops/ms
Iteration   1: 13.842 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.842 ops/ms


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
# Warmup Iteration   1: 4.103 ops/ms
Iteration   1: 8.950 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.950 ops/ms


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
# Warmup Iteration   1: 2.111 ops/ms
Iteration   1: 3.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.665 ops/ms


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.069 ms/op
Iteration   1: 3.160 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.160 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.046 ms/op
Iteration   1: 1.698 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.698 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.891 ±(99.9%) 0.059 ms/op
Iteration   1: 2.973 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.973 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.065 ±(99.9%) 0.196 ms/op
Iteration   1: 7.919 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.919 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.951 ±(99.9%) 0.111 ms/op
Iteration   1: 3.204 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   10.110 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9975
  mean =      3.204 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2077 
    [ 2.500,  3.750) = 6579 
    [ 3.750,  5.000) = 893 
    [ 5.000,  6.250) = 203 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =     10.110 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.089 ms/op
Iteration   1: 1.739 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   1.614 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   4.183 ms/op
                 existUser·p0.999:  5.261 ms/op
                 existUser·p0.9999: 7.898 ms/op
                 existUser·p1.00:   7.905 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18375
  mean =      1.739 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 265 
    [1.000, 1.500) = 6662 
    [1.500, 2.000) = 7356 
    [2.000, 2.500) = 3002 
    [2.500, 3.000) = 677 
    [3.000, 3.500) = 192 
    [3.500, 4.000) = 32 
    [4.000, 4.500) = 121 
    [4.500, 5.000) = 18 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.614 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      4.183 ms/op
     p(99.9000) =      5.261 ms/op
     p(99.9900) =      7.898 ms/op
     p(99.9990) =      7.905 ms/op
     p(99.9999) =      7.905 ms/op
    p(100.0000) =      7.905 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.114 ms/op
Iteration   1: 2.995 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.822 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.095 ms/op
                 getUser·p0.99:   5.920 ms/op
                 getUser·p0.999:  16.318 ms/op
                 getUser·p0.9999: 20.969 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10684
  mean =      2.995 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3649 
    [ 2.500,  5.000) = 6850 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.095 ms/op
     p(99.0000) =      5.920 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     20.969 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 12.605 ±(99.9%) 0.462 ms/op
Iteration   1: 8.504 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   3.351 ms/op
                 listUser·p0.50:   8.167 ms/op
                 listUser·p0.90:   11.485 ms/op
                 listUser·p0.95:   12.452 ms/op
                 listUser·p0.99:   15.408 ms/op
                 listUser·p0.999:  23.260 ms/op
                 listUser·p0.9999: 29.983 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3759
  mean =      8.504 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1249 
    [ 7.500, 10.000) = 1608 
    [10.000, 12.500) = 611 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.351 ms/op
     p(50.0000) =      8.167 ms/op
     p(90.0000) =     11.485 ms/op
     p(95.0000) =     12.452 ms/op
     p(99.0000) =     15.408 ms/op
     p(99.9000) =     23.260 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.938          ops/ms
Client.existUser                       thrpt         13.842          ops/ms
Client.getUser                         thrpt          8.950          ops/ms
Client.listUser                        thrpt          3.665          ops/ms
Client.createUser                       avgt          3.160           ms/op
Client.existUser                        avgt          1.698           ms/op
Client.getUser                          avgt          2.973           ms/op
Client.listUser                         avgt          7.919           ms/op
Client.createUser                     sample   9975   3.204 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.337           ms/op
Client.createUser:createUser·p0.50    sample          3.015           ms/op
Client.createUser:createUser·p0.90    sample          4.030           ms/op
Client.createUser:createUser·p0.95    sample          4.768           ms/op
Client.createUser:createUser·p0.99    sample         10.110           ms/op
Client.createUser:createUser·p0.999   sample         16.630           ms/op
Client.createUser:createUser·p0.9999  sample         16.908           ms/op
Client.createUser:createUser·p1.00    sample         16.908           ms/op
Client.existUser                      sample  18375   1.739 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.682           ms/op
Client.existUser:existUser·p0.50      sample          1.614           ms/op
Client.existUser:existUser·p0.90      sample          2.351           ms/op
Client.existUser:existUser·p0.95      sample          2.540           ms/op
Client.existUser:existUser·p0.99      sample          4.183           ms/op
Client.existUser:existUser·p0.999     sample          5.261           ms/op
Client.existUser:existUser·p0.9999    sample          7.898           ms/op
Client.existUser:existUser·p1.00      sample          7.905           ms/op
Client.getUser                        sample  10684   2.995 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          0.706           ms/op
Client.getUser:getUser·p0.50          sample          2.822           ms/op
Client.getUser:getUser·p0.90          sample          3.785           ms/op
Client.getUser:getUser·p0.95          sample          4.095           ms/op
Client.getUser:getUser·p0.99          sample          5.920           ms/op
Client.getUser:getUser·p0.999         sample         16.318           ms/op
Client.getUser:getUser·p0.9999        sample         20.969           ms/op
Client.getUser:getUser·p1.00          sample         20.972           ms/op
Client.listUser                       sample   3759   8.504 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          3.351           ms/op
Client.listUser:listUser·p0.50        sample          8.167           ms/op
Client.listUser:listUser·p0.90        sample         11.485           ms/op
Client.listUser:listUser·p0.95        sample         12.452           ms/op
Client.listUser:listUser·p0.99        sample         15.408           ms/op
Client.listUser:listUser·p0.999       sample         23.260           ms/op
Client.listUser:listUser·p0.9999      sample         29.983           ms/op
Client.listUser:listUser·p1.00        sample         29.983           ms/op
