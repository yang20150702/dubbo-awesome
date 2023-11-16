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
# Warmup Iteration   1: 2.348 ops/ms
Iteration   1: 5.698 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.698 ops/ms


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
# Warmup Iteration   1: 6.662 ops/ms
Iteration   1: 12.142 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.142 ops/ms


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
# Warmup Iteration   1: 4.433 ops/ms
Iteration   1: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.226 ops/ms


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
# Warmup Iteration   1: 2.089 ops/ms
Iteration   1: 3.354 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.354 ops/ms


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
# Warmup Iteration   1: 4.908 ±(99.9%) 0.075 ms/op
Iteration   1: 2.882 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.882 ms/op


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
# Warmup Iteration   1: 2.724 ±(99.9%) 0.033 ms/op
Iteration   1: 1.737 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.737 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.056 ms/op
Iteration   1: 2.986 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.986 ms/op


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
# Warmup Iteration   1: 13.174 ±(99.9%) 0.254 ms/op
Iteration   1: 8.389 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.389 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.101 ms/op
Iteration   1: 3.070 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   8.222 ms/op
                 createUser·p0.999:  14.616 ms/op
                 createUser·p0.9999: 16.331 ms/op
                 createUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10408
  mean =      3.070 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1219 
    [ 2.500,  3.750) = 8271 
    [ 3.750,  5.000) = 457 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      8.222 ms/op
     p(99.9000) =     14.616 ms/op
     p(99.9900) =     16.331 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 3.479 ±(99.9%) 0.100 ms/op
Iteration   1: 1.824 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 13.431 ms/op
                 existUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17695
  mean =      1.824 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1244 
    [ 1.250,  2.500) = 15298 
    [ 2.500,  3.750) = 1018 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.431 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 4.465 ±(99.9%) 0.102 ms/op
Iteration   1: 3.077 ±(99.9%) 0.137 ms/op
                 getUser·p0.00:   0.424 ms/op
                 getUser·p0.50:   2.699 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  86.198 ms/op
                 getUser·p0.9999: 91.829 ms/op
                 getUser·p1.00:   91.881 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10397
  mean =      3.077 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 10312 
    [ 10.000,  20.000) = 40 
    [ 20.000,  30.000) = 2 
    [ 30.000,  40.000) = 8 
    [ 40.000,  50.000) = 4 
    [ 50.000,  60.000) = 10 
    [ 60.000,  70.000) = 2 
    [ 70.000,  80.000) = 4 
    [ 80.000,  90.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.699 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     86.198 ms/op
     p(99.9900) =     91.829 ms/op
     p(99.9990) =     91.881 ms/op
     p(99.9999) =     91.881 ms/op
    p(100.0000) =     91.881 ms/op


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
# Warmup Iteration   1: 11.681 ±(99.9%) 0.370 ms/op
Iteration   1: 8.149 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   11.010 ms/op
                 listUser·p0.95:   12.075 ms/op
                 listUser·p0.99:   14.631 ms/op
                 listUser·p0.999:  29.190 ms/op
                 listUser·p0.9999: 37.224 ms/op
                 listUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3927
  mean =      8.149 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 173 
    [ 5.000,  7.500) = 1558 
    [ 7.500, 10.000) = 1518 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.777 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     11.010 ms/op
     p(95.0000) =     12.075 ms/op
     p(99.0000) =     14.631 ms/op
     p(99.9000) =     29.190 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.698          ops/ms
Client.existUser                       thrpt         12.142          ops/ms
Client.getUser                         thrpt          9.226          ops/ms
Client.listUser                        thrpt          3.354          ops/ms
Client.createUser                       avgt          2.882           ms/op
Client.existUser                        avgt          1.737           ms/op
Client.getUser                          avgt          2.986           ms/op
Client.listUser                         avgt          8.389           ms/op
Client.createUser                     sample  10408   3.070 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.928           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          3.645           ms/op
Client.createUser:createUser·p0.95    sample          4.465           ms/op
Client.createUser:createUser·p0.99    sample          8.222           ms/op
Client.createUser:createUser·p0.999   sample         14.616           ms/op
Client.createUser:createUser·p0.9999  sample         16.331           ms/op
Client.createUser:createUser·p1.00    sample         16.335           ms/op
Client.existUser                      sample  17695   1.824 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.549           ms/op
Client.existUser:existUser·p0.50      sample          1.729           ms/op
Client.existUser:existUser·p0.90      sample          2.347           ms/op
Client.existUser:existUser·p0.95      sample          2.646           ms/op
Client.existUser:existUser·p0.99      sample          3.555           ms/op
Client.existUser:existUser·p0.999     sample         13.058           ms/op
Client.existUser:existUser·p0.9999    sample         13.431           ms/op
Client.existUser:existUser·p1.00      sample         13.746           ms/op
Client.getUser                        sample  10397   3.077 ± 0.137   ms/op
Client.getUser:getUser·p0.00          sample          0.424           ms/op
Client.getUser:getUser·p0.50          sample          2.699           ms/op
Client.getUser:getUser·p0.90          sample          3.514           ms/op
Client.getUser:getUser·p0.95          sample          3.863           ms/op
Client.getUser:getUser·p0.99          sample          7.791           ms/op
Client.getUser:getUser·p0.999         sample         86.198           ms/op
Client.getUser:getUser·p0.9999        sample         91.829           ms/op
Client.getUser:getUser·p1.00          sample         91.881           ms/op
Client.listUser                       sample   3927   8.149 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          2.777           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         11.010           ms/op
Client.listUser:listUser·p0.95        sample         12.075           ms/op
Client.listUser:listUser·p0.99        sample         14.631           ms/op
Client.listUser:listUser·p0.999       sample         29.190           ms/op
Client.listUser:listUser·p0.9999      sample         37.224           ms/op
Client.listUser:listUser·p1.00        sample         37.224           ms/op
