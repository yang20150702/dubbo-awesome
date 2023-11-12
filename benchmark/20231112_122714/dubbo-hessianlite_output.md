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
# Warmup Iteration   1: 2.686 ops/ms
Iteration   1: 5.787 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.787 ops/ms


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
# Warmup Iteration   1: 6.650 ops/ms
Iteration   1: 14.398 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.398 ops/ms


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
# Warmup Iteration   1: 5.136 ops/ms
Iteration   1: 9.490 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.490 ops/ms


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
# Warmup Iteration   1: 2.480 ops/ms
Iteration   1: 3.628 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.628 ops/ms


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.073 ms/op
Iteration   1: 3.031 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.031 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.034 ms/op
Iteration   1: 1.854 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.854 ms/op


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.047 ms/op
Iteration   1: 3.381 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.381 ms/op


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
# Warmup Iteration   1: 10.521 ±(99.9%) 0.220 ms/op
Iteration   1: 7.455 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.455 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.084 ms/op
Iteration   1: 2.928 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.559 ms/op
                 createUser·p0.99:   6.130 ms/op
                 createUser·p0.999:  27.296 ms/op
                 createUser·p0.9999: 28.360 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11088
  mean =      2.928 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3468 
    [ 2.500,  5.000) = 7189 
    [ 5.000,  7.500) = 365 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.559 ms/op
     p(99.0000) =      6.130 ms/op
     p(99.9000) =     27.296 ms/op
     p(99.9900) =     28.360 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ±(99.9%) 0.054 ms/op
Iteration   1: 1.789 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.714 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  5.189 ms/op
                 existUser·p0.9999: 5.400 ms/op
                 existUser·p1.00:   5.407 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17919
  mean =      1.789 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 86 
    [1.000, 1.500) = 3586 
    [1.500, 2.000) = 9881 
    [2.000, 2.500) = 3601 
    [2.500, 3.000) = 554 
    [3.000, 3.500) = 56 
    [3.500, 4.000) = 55 
    [4.000, 4.500) = 51 
    [4.500, 5.000) = 5 
    [5.000, 5.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.359 ms/op
     p(99.9000) =      5.189 ms/op
     p(99.9900) =      5.400 ms/op
     p(99.9990) =      5.407 ms/op
     p(99.9999) =      5.407 ms/op
    p(100.0000) =      5.407 ms/op


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.095 ms/op
Iteration   1: 2.939 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.888 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.719 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10996
  mean =      2.939 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 3594 
    [ 2.500,  3.750) = 6443 
    [ 3.750,  5.000) = 777 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.719 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 11.126 ±(99.9%) 0.316 ms/op
Iteration   1: 8.129 ±(99.9%) 0.108 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   7.873 ms/op
                 listUser·p0.90:   10.715 ms/op
                 listUser·p0.95:   11.873 ms/op
                 listUser·p0.99:   15.076 ms/op
                 listUser·p0.999:  16.572 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3926
  mean =      8.129 ±(99.9%) 0.108 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 9 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 1027 
    [ 7.500,  8.750) = 1000 
    [ 8.750, 10.000) = 644 
    [10.000, 11.250) = 341 
    [11.250, 12.500) = 154 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      7.873 ms/op
     p(90.0000) =     10.715 ms/op
     p(95.0000) =     11.873 ms/op
     p(99.0000) =     15.076 ms/op
     p(99.9000) =     16.572 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.787          ops/ms
Client.existUser                       thrpt         14.398          ops/ms
Client.getUser                         thrpt          9.490          ops/ms
Client.listUser                        thrpt          3.628          ops/ms
Client.createUser                       avgt          3.031           ms/op
Client.existUser                        avgt          1.854           ms/op
Client.getUser                          avgt          3.381           ms/op
Client.listUser                         avgt          7.455           ms/op
Client.createUser                     sample  11088   2.928 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.167           ms/op
Client.createUser:createUser·p0.50    sample          2.650           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          4.559           ms/op
Client.createUser:createUser·p0.99    sample          6.130           ms/op
Client.createUser:createUser·p0.999   sample         27.296           ms/op
Client.createUser:createUser·p0.9999  sample         28.360           ms/op
Client.createUser:createUser·p1.00    sample         28.410           ms/op
Client.existUser                      sample  17919   1.789 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.634           ms/op
Client.existUser:existUser·p0.50      sample          1.714           ms/op
Client.existUser:existUser·p0.90      sample          2.265           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          3.359           ms/op
Client.existUser:existUser·p0.999     sample          5.189           ms/op
Client.existUser:existUser·p0.9999    sample          5.400           ms/op
Client.existUser:existUser·p1.00      sample          5.407           ms/op
Client.getUser                        sample  10996   2.939 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.851           ms/op
Client.getUser:getUser·p0.50          sample          2.888           ms/op
Client.getUser:getUser·p0.90          sample          3.670           ms/op
Client.getUser:getUser·p0.95          sample          3.957           ms/op
Client.getUser:getUser·p0.99          sample          5.719           ms/op
Client.getUser:getUser·p0.999         sample         19.333           ms/op
Client.getUser:getUser·p0.9999        sample         19.497           ms/op
Client.getUser:getUser·p1.00          sample         19.497           ms/op
Client.listUser                       sample   3926   8.129 ± 0.108   ms/op
Client.listUser:listUser·p0.00        sample          2.372           ms/op
Client.listUser:listUser·p0.50        sample          7.873           ms/op
Client.listUser:listUser·p0.90        sample         10.715           ms/op
Client.listUser:listUser·p0.95        sample         11.873           ms/op
Client.listUser:listUser·p0.99        sample         15.076           ms/op
Client.listUser:listUser·p0.999       sample         16.572           ms/op
Client.listUser:listUser·p0.9999      sample         17.760           ms/op
Client.listUser:listUser·p1.00        sample         17.760           ms/op
