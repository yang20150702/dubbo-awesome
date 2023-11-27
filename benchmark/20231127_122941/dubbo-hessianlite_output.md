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
# Warmup Iteration   1: 2.131 ops/ms
Iteration   1: 6.435 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.435 ops/ms


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
# Warmup Iteration   1: 6.011 ops/ms
Iteration   1: 14.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.377 ops/ms


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
# Warmup Iteration   1: 4.335 ops/ms
Iteration   1: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.831 ops/ms


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
# Warmup Iteration   1: 2.658 ops/ms
Iteration   1: 3.655 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.655 ops/ms


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.095 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.097 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.038 ms/op
Iteration   1: 1.883 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.883 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.049 ms/op
Iteration   1: 3.240 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.240 ms/op


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
# Warmup Iteration   1: 10.981 ±(99.9%) 0.209 ms/op
Iteration   1: 7.016 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.016 ms/op


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.101 ms/op
Iteration   1: 2.980 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   4.024 ms/op
                 createUser·p0.99:   12.747 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 18.737 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10930
  mean =      2.980 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2874 
    [ 2.500,  3.750) = 7278 
    [ 3.750,  5.000) = 513 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.024 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     18.737 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.056 ms/op
Iteration   1: 1.829 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 10.897 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17476
  mean =      1.829 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 609 
    [ 1.250,  2.500) = 16082 
    [ 2.500,  3.750) = 630 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     10.897 ms/op
     p(99.9990) =     11.583 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


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
# Warmup Iteration   1: 4.910 ±(99.9%) 0.221 ms/op
Iteration   1: 3.445 ±(99.9%) 0.159 ms/op
                 getUser·p0.00:   0.393 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   13.834 ms/op
                 getUser·p0.999:  87.112 ms/op
                 getUser·p0.9999: 91.750 ms/op
                 getUser·p1.00:   91.750 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9387
  mean =      3.445 ±(99.9%) 0.159 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 9239 
    [ 10.000,  20.000) = 83 
    [ 20.000,  30.000) = 27 
    [ 30.000,  40.000) = 5 
    [ 40.000,  50.000) = 1 
    [ 50.000,  60.000) = 6 
    [ 60.000,  70.000) = 4 
    [ 70.000,  80.000) = 6 
    [ 80.000,  90.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =     13.834 ms/op
     p(99.9000) =     87.112 ms/op
     p(99.9900) =     91.750 ms/op
     p(99.9990) =     91.750 ms/op
     p(99.9999) =     91.750 ms/op
    p(100.0000) =     91.750 ms/op


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
# Warmup Iteration   1: 12.592 ±(99.9%) 0.382 ms/op
Iteration   1: 8.589 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   3.703 ms/op
                 listUser·p0.50:   8.159 ms/op
                 listUser·p0.90:   11.600 ms/op
                 listUser·p0.95:   12.386 ms/op
                 listUser·p0.99:   15.864 ms/op
                 listUser·p0.999:  20.744 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3824
  mean =      8.589 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 45 
    [ 5.000,  7.500) = 1368 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 765 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.703 ms/op
     p(50.0000) =      8.159 ms/op
     p(90.0000) =     11.600 ms/op
     p(95.0000) =     12.386 ms/op
     p(99.0000) =     15.864 ms/op
     p(99.9000) =     20.744 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.435          ops/ms
Client.existUser                       thrpt         14.377          ops/ms
Client.getUser                         thrpt          9.831          ops/ms
Client.listUser                        thrpt          3.655          ops/ms
Client.createUser                       avgt          3.097           ms/op
Client.existUser                        avgt          1.883           ms/op
Client.getUser                          avgt          3.240           ms/op
Client.listUser                         avgt          7.016           ms/op
Client.createUser                     sample  10930   2.980 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.067           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.527           ms/op
Client.createUser:createUser·p0.95    sample          4.024           ms/op
Client.createUser:createUser·p0.99    sample         12.747           ms/op
Client.createUser:createUser·p0.999   sample         17.531           ms/op
Client.createUser:createUser·p0.9999  sample         18.737           ms/op
Client.createUser:createUser·p1.00    sample         18.743           ms/op
Client.existUser                      sample  17476   1.829 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.460           ms/op
Client.existUser:existUser·p0.50      sample          1.761           ms/op
Client.existUser:existUser·p0.90      sample          2.224           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          3.719           ms/op
Client.existUser:existUser·p0.999     sample         10.387           ms/op
Client.existUser:existUser·p0.9999    sample         10.897           ms/op
Client.existUser:existUser·p1.00      sample         11.583           ms/op
Client.getUser                        sample   9387   3.445 ± 0.159   ms/op
Client.getUser:getUser·p0.00          sample          0.393           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          3.912           ms/op
Client.getUser:getUser·p0.95          sample          4.653           ms/op
Client.getUser:getUser·p0.99          sample         13.834           ms/op
Client.getUser:getUser·p0.999         sample         87.112           ms/op
Client.getUser:getUser·p0.9999        sample         91.750           ms/op
Client.getUser:getUser·p1.00          sample         91.750           ms/op
Client.listUser                       sample   3824   8.589 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          3.703           ms/op
Client.listUser:listUser·p0.50        sample          8.159           ms/op
Client.listUser:listUser·p0.90        sample         11.600           ms/op
Client.listUser:listUser·p0.95        sample         12.386           ms/op
Client.listUser:listUser·p0.99        sample         15.864           ms/op
Client.listUser:listUser·p0.999       sample         20.744           ms/op
Client.listUser:listUser·p0.9999      sample         23.462           ms/op
Client.listUser:listUser·p1.00        sample         23.462           ms/op
