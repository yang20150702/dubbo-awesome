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
# Warmup Iteration   1: 2.398 ops/ms
Iteration   1: 6.175 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.175 ops/ms


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
# Warmup Iteration   1: 6.121 ops/ms
Iteration   1: 12.580 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.580 ops/ms


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
# Warmup Iteration   1: 4.990 ops/ms
Iteration   1: 9.717 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.717 ops/ms


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
# Warmup Iteration   1: 2.244 ops/ms
Iteration   1: 3.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.732 ops/ms


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
# Warmup Iteration   1: 5.192 ±(99.9%) 0.071 ms/op
Iteration   1: 2.877 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.877 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.032 ms/op
Iteration   1: 1.834 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.834 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.052 ms/op
Iteration   1: 2.970 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.970 ms/op


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
# Warmup Iteration   1: 12.056 ±(99.9%) 0.199 ms/op
Iteration   1: 8.358 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.358 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.110 ms/op
Iteration   1: 2.851 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   6.221 ms/op
                 createUser·p0.999:  30.409 ms/op
                 createUser·p0.9999: 31.350 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11405
  mean =      2.851 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3642 
    [ 2.500,  5.000) = 7586 
    [ 5.000,  7.500) = 113 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      6.221 ms/op
     p(99.9000) =     30.409 ms/op
     p(99.9900) =     31.350 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 3.119 ±(99.9%) 0.076 ms/op
Iteration   1: 2.165 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.154 ms/op
                 existUser·p0.90:   2.646 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   3.421 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 9.462 ms/op
                 existUser·p1.00:   9.470 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14777
  mean =      2.165 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 50 
    [ 1.000,  2.000) = 4937 
    [ 2.000,  3.000) = 9388 
    [ 3.000,  4.000) = 286 
    [ 4.000,  5.000) = 58 
    [ 5.000,  6.000) = 20 
    [ 6.000,  7.000) = 6 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.421 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =      9.462 ms/op
     p(99.9990) =      9.470 ms/op
     p(99.9999) =      9.470 ms/op
    p(100.0000) =      9.470 ms/op


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.095 ms/op
Iteration   1: 2.766 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.114 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 13.743 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11673
  mean =      2.766 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 5123 
    [ 2.500,  3.750) = 5633 
    [ 3.750,  5.000) = 767 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.114 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     13.743 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 10.895 ±(99.9%) 0.328 ms/op
Iteration   1: 8.187 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   3.125 ms/op
                 listUser·p0.50:   7.623 ms/op
                 listUser·p0.90:   11.333 ms/op
                 listUser·p0.95:   12.851 ms/op
                 listUser·p0.99:   19.067 ms/op
                 listUser·p0.999:  22.094 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3912
  mean =      8.187 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 102 
    [ 5.000,  7.500) = 1737 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.125 ms/op
     p(50.0000) =      7.623 ms/op
     p(90.0000) =     11.333 ms/op
     p(95.0000) =     12.851 ms/op
     p(99.0000) =     19.067 ms/op
     p(99.9000) =     22.094 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.175          ops/ms
Client.existUser                       thrpt         12.580          ops/ms
Client.getUser                         thrpt          9.717          ops/ms
Client.listUser                        thrpt          3.732          ops/ms
Client.createUser                       avgt          2.877           ms/op
Client.existUser                        avgt          1.834           ms/op
Client.getUser                          avgt          2.970           ms/op
Client.listUser                         avgt          8.358           ms/op
Client.createUser                     sample  11405   2.851 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          0.940           ms/op
Client.createUser:createUser·p0.50    sample          2.687           ms/op
Client.createUser:createUser·p0.90    sample          3.420           ms/op
Client.createUser:createUser·p0.95    sample          3.932           ms/op
Client.createUser:createUser·p0.99    sample          6.221           ms/op
Client.createUser:createUser·p0.999   sample         30.409           ms/op
Client.createUser:createUser·p0.9999  sample         31.350           ms/op
Client.createUser:createUser·p1.00    sample         31.392           ms/op
Client.existUser                      sample  14777   2.165 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.606           ms/op
Client.existUser:existUser·p0.50      sample          2.154           ms/op
Client.existUser:existUser·p0.90      sample          2.646           ms/op
Client.existUser:existUser·p0.95      sample          2.834           ms/op
Client.existUser:existUser·p0.99      sample          3.421           ms/op
Client.existUser:existUser·p0.999     sample          9.322           ms/op
Client.existUser:existUser·p0.9999    sample          9.462           ms/op
Client.existUser:existUser·p1.00      sample          9.470           ms/op
Client.getUser                        sample  11673   2.766 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.545           ms/op
Client.getUser:getUser·p0.50          sample          2.589           ms/op
Client.getUser:getUser·p0.90          sample          3.621           ms/op
Client.getUser:getUser·p0.95          sample          3.912           ms/op
Client.getUser:getUser·p0.99          sample          5.114           ms/op
Client.getUser:getUser·p0.999         sample         13.664           ms/op
Client.getUser:getUser·p0.9999        sample         13.743           ms/op
Client.getUser:getUser·p1.00          sample         13.746           ms/op
Client.listUser                       sample   3912   8.187 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          3.125           ms/op
Client.listUser:listUser·p0.50        sample          7.623           ms/op
Client.listUser:listUser·p0.90        sample         11.333           ms/op
Client.listUser:listUser·p0.95        sample         12.851           ms/op
Client.listUser:listUser·p0.99        sample         19.067           ms/op
Client.listUser:listUser·p0.999       sample         22.094           ms/op
Client.listUser:listUser·p0.9999      sample         22.184           ms/op
Client.listUser:listUser·p1.00        sample         22.184           ms/op
