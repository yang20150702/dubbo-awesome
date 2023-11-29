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
# Warmup Iteration   1: 2.492 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.843 ops/ms


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
# Warmup Iteration   1: 6.714 ops/ms
Iteration   1: 13.239 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.239 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.940 ops/ms
Iteration   1: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.165 ops/ms


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
# Warmup Iteration   1: 2.698 ops/ms
Iteration   1: 4.414 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.414 ops/ms


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.080 ms/op
Iteration   1: 2.877 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.877 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.042 ms/op
Iteration   1: 1.907 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.056 ms/op
Iteration   1: 2.693 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.693 ms/op


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
# Warmup Iteration   1: 12.105 ±(99.9%) 0.255 ms/op
Iteration   1: 8.439 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.439 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.077 ms/op
Iteration   1: 3.104 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.739 ms/op
                 createUser·p0.99:   11.023 ms/op
                 createUser·p0.999:  27.283 ms/op
                 createUser·p0.9999: 27.846 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10389
  mean =      3.104 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1992 
    [ 2.500,  5.000) = 8006 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.739 ms/op
     p(99.0000) =     11.023 ms/op
     p(99.9000) =     27.283 ms/op
     p(99.9900) =     27.846 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.076 ms/op
Iteration   1: 1.629 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   1.544 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   2.983 ms/op
                 existUser·p0.999:  4.787 ms/op
                 existUser·p0.9999: 8.433 ms/op
                 existUser·p1.00:   9.159 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19624
  mean =      1.629 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 376 
    [ 1.000,  2.000) = 15964 
    [ 2.000,  3.000) = 3095 
    [ 3.000,  4.000) = 79 
    [ 4.000,  5.000) = 96 
    [ 5.000,  6.000) = 7 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.544 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.983 ms/op
     p(99.9000) =      4.787 ms/op
     p(99.9900) =      8.433 ms/op
     p(99.9990) =      9.159 ms/op
     p(99.9999) =      9.159 ms/op
    p(100.0000) =      9.159 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.099 ms/op
Iteration   1: 2.875 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.818 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.019 ms/op
                 getUser·p0.999:  13.465 ms/op
                 getUser·p0.9999: 14.485 ms/op
                 getUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11136
  mean =      2.875 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 3345 
    [ 2.500,  3.750) = 7135 
    [ 3.750,  5.000) = 526 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.019 ms/op
     p(99.9000) =     13.465 ms/op
     p(99.9900) =     14.485 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 11.790 ±(99.9%) 0.348 ms/op
Iteration   1: 7.423 ±(99.9%) 0.091 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   7.119 ms/op
                 listUser·p0.90:   9.781 ms/op
                 listUser·p0.95:   10.845 ms/op
                 listUser·p0.99:   13.650 ms/op
                 listUser·p0.999:  17.486 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4340
  mean =      7.423 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 23 
    [ 3.750,  5.000) = 180 
    [ 5.000,  6.250) = 863 
    [ 6.250,  7.500) = 1516 
    [ 7.500,  8.750) = 961 
    [ 8.750, 10.000) = 425 
    [10.000, 11.250) = 210 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      7.119 ms/op
     p(90.0000) =      9.781 ms/op
     p(95.0000) =     10.845 ms/op
     p(99.0000) =     13.650 ms/op
     p(99.9000) =     17.486 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.843          ops/ms
Client.existUser                       thrpt         13.239          ops/ms
Client.getUser                         thrpt          9.165          ops/ms
Client.listUser                        thrpt          4.414          ops/ms
Client.createUser                       avgt          2.877           ms/op
Client.existUser                        avgt          1.907           ms/op
Client.getUser                          avgt          2.693           ms/op
Client.listUser                         avgt          8.439           ms/op
Client.createUser                     sample  10389   3.104 ± 0.061   ms/op
Client.createUser:createUser·p0.00    sample          1.169           ms/op
Client.createUser:createUser·p0.50    sample          2.712           ms/op
Client.createUser:createUser·p0.90    sample          3.727           ms/op
Client.createUser:createUser·p0.95    sample          4.739           ms/op
Client.createUser:createUser·p0.99    sample         11.023           ms/op
Client.createUser:createUser·p0.999   sample         27.283           ms/op
Client.createUser:createUser·p0.9999  sample         27.846           ms/op
Client.createUser:createUser·p1.00    sample         27.853           ms/op
Client.existUser                      sample  19624   1.629 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.495           ms/op
Client.existUser:existUser·p0.50      sample          1.544           ms/op
Client.existUser:existUser·p0.90      sample          2.159           ms/op
Client.existUser:existUser·p0.95      sample          2.355           ms/op
Client.existUser:existUser·p0.99      sample          2.983           ms/op
Client.existUser:existUser·p0.999     sample          4.787           ms/op
Client.existUser:existUser·p0.9999    sample          8.433           ms/op
Client.existUser:existUser·p1.00      sample          9.159           ms/op
Client.getUser                        sample  11136   2.875 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.849           ms/op
Client.getUser:getUser·p0.50          sample          2.818           ms/op
Client.getUser:getUser·p0.90          sample          3.572           ms/op
Client.getUser:getUser·p0.95          sample          3.797           ms/op
Client.getUser:getUser·p0.99          sample          5.019           ms/op
Client.getUser:getUser·p0.999         sample         13.465           ms/op
Client.getUser:getUser·p0.9999        sample         14.485           ms/op
Client.getUser:getUser·p1.00          sample         14.598           ms/op
Client.listUser                       sample   4340   7.423 ± 0.091   ms/op
Client.listUser:listUser·p0.00        sample          2.281           ms/op
Client.listUser:listUser·p0.50        sample          7.119           ms/op
Client.listUser:listUser·p0.90        sample          9.781           ms/op
Client.listUser:listUser·p0.95        sample         10.845           ms/op
Client.listUser:listUser·p0.99        sample         13.650           ms/op
Client.listUser:listUser·p0.999       sample         17.486           ms/op
Client.listUser:listUser·p0.9999      sample         18.219           ms/op
Client.listUser:listUser·p1.00        sample         18.219           ms/op
