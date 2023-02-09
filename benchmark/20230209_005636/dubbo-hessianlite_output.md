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
# Warmup Iteration   1: 1.056 ops/ms
Iteration   1: 2.465 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.465 ops/ms


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
# Warmup Iteration   1: 2.705 ops/ms
Iteration   1: 6.594 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.594 ops/ms


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
# Warmup Iteration   1: 1.711 ops/ms
Iteration   1: 4.237 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.237 ops/ms


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
# Warmup Iteration   1: 1.070 ops/ms
Iteration   1: 1.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.410 ops/ms


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
# Warmup Iteration   1: 13.988 ±(99.9%) 0.245 ms/op
Iteration   1: 6.940 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.940 ms/op


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
# Warmup Iteration   1: 6.609 ±(99.9%) 0.063 ms/op
Iteration   1: 3.687 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.687 ms/op


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
# Warmup Iteration   1: 9.047 ±(99.9%) 0.097 ms/op
Iteration   1: 4.505 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.505 ms/op


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
# Warmup Iteration   1: 24.944 ±(99.9%) 0.333 ms/op
Iteration   1: 16.707 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.707 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.372 ±(99.9%) 0.287 ms/op
Iteration   1: 5.061 ±(99.9%) 0.088 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   5.923 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   15.532 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6357
  mean =      5.061 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 245 
    [ 2.500,  5.000) = 3089 
    [ 5.000,  7.500) = 2716 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     15.532 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 6.880 ±(99.9%) 0.213 ms/op
Iteration   1: 3.619 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  14.297 ms/op
                 existUser·p0.9999: 14.647 ms/op
                 existUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8842
  mean =      3.619 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 1073 
    [ 2.500,  3.750) = 3257 
    [ 3.750,  5.000) = 4328 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     14.297 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 7.236 ±(99.9%) 0.261 ms/op
Iteration   1: 4.436 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  9.740 ms/op
                 getUser·p0.9999: 10.125 ms/op
                 getUser·p1.00:   10.125 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7250
  mean =      4.436 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 4 
    [ 2.000,  3.000) = 101 
    [ 3.000,  4.000) = 1592 
    [ 4.000,  5.000) = 4634 
    [ 5.000,  6.000) = 730 
    [ 6.000,  7.000) = 62 
    [ 7.000,  8.000) = 47 
    [ 8.000,  9.000) = 60 
    [ 9.000, 10.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =      9.740 ms/op
     p(99.9900) =     10.125 ms/op
     p(99.9990) =     10.125 ms/op
     p(99.9999) =     10.125 ms/op
    p(100.0000) =     10.125 ms/op


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
# Warmup Iteration   1: 26.152 ±(99.9%) 0.562 ms/op
Iteration   1: 17.902 ±(99.9%) 0.335 ms/op
                 listUser·p0.00:   7.406 ms/op
                 listUser·p0.50:   18.153 ms/op
                 listUser·p0.90:   21.158 ms/op
                 listUser·p0.95:   23.686 ms/op
                 listUser·p0.99:   36.110 ms/op
                 listUser·p0.999:  41.244 ms/op
                 listUser·p0.9999: 42.402 ms/op
                 listUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1802
  mean =     17.902 ±(99.9%) 0.335 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 31 
    [10.000, 15.000) = 304 
    [15.000, 20.000) = 1113 
    [20.000, 25.000) = 277 
    [25.000, 30.000) = 45 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      7.406 ms/op
     p(50.0000) =     18.153 ms/op
     p(90.0000) =     21.158 ms/op
     p(95.0000) =     23.686 ms/op
     p(99.0000) =     36.110 ms/op
     p(99.9000) =     41.244 ms/op
     p(99.9900) =     42.402 ms/op
     p(99.9990) =     42.402 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.465          ops/ms
Client.existUser                       thrpt         6.594          ops/ms
Client.getUser                         thrpt         4.237          ops/ms
Client.listUser                        thrpt         1.410          ops/ms
Client.createUser                       avgt         6.940           ms/op
Client.existUser                        avgt         3.687           ms/op
Client.getUser                          avgt         4.505           ms/op
Client.listUser                         avgt        16.707           ms/op
Client.createUser                     sample  6357   5.061 ± 0.088   ms/op
Client.createUser:createUser·p0.00    sample         1.110           ms/op
Client.createUser:createUser·p0.50    sample         4.866           ms/op
Client.createUser:createUser·p0.90    sample         5.923           ms/op
Client.createUser:createUser·p0.95    sample         7.307           ms/op
Client.createUser:createUser·p0.99    sample        15.532           ms/op
Client.createUser:createUser·p0.999   sample        20.447           ms/op
Client.createUser:createUser·p0.9999  sample        20.709           ms/op
Client.createUser:createUser·p1.00    sample        20.709           ms/op
Client.existUser                      sample  8842   3.619 ± 0.037   ms/op
Client.existUser:existUser·p0.00      sample         0.759           ms/op
Client.existUser:existUser·p0.50      sample         3.756           ms/op
Client.existUser:existUser·p0.90      sample         4.166           ms/op
Client.existUser:existUser·p0.95      sample         4.399           ms/op
Client.existUser:existUser·p0.99      sample         5.636           ms/op
Client.existUser:existUser·p0.999     sample        14.297           ms/op
Client.existUser:existUser·p0.9999    sample        14.647           ms/op
Client.existUser:existUser·p1.00      sample        14.647           ms/op
Client.getUser                        sample  7250   4.436 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample         1.507           ms/op
Client.getUser:getUser·p0.50          sample         4.301           ms/op
Client.getUser:getUser·p0.90          sample         5.104           ms/op
Client.getUser:getUser·p0.95          sample         5.382           ms/op
Client.getUser:getUser·p0.99          sample         8.307           ms/op
Client.getUser:getUser·p0.999         sample         9.740           ms/op
Client.getUser:getUser·p0.9999        sample        10.125           ms/op
Client.getUser:getUser·p1.00          sample        10.125           ms/op
Client.listUser                       sample  1802  17.902 ± 0.335   ms/op
Client.listUser:listUser·p0.00        sample         7.406           ms/op
Client.listUser:listUser·p0.50        sample        18.153           ms/op
Client.listUser:listUser·p0.90        sample        21.158           ms/op
Client.listUser:listUser·p0.95        sample        23.686           ms/op
Client.listUser:listUser·p0.99        sample        36.110           ms/op
Client.listUser:listUser·p0.999       sample        41.244           ms/op
Client.listUser:listUser·p0.9999      sample        42.402           ms/op
Client.listUser:listUser·p1.00        sample        42.402           ms/op
