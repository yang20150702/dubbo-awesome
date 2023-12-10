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
# Warmup Iteration   1: 2.316 ops/ms
Iteration   1: 6.458 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.458 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.180 ops/ms
Iteration   1: 14.679 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.679 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ops/ms
Iteration   1: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.523 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.135 ops/ms
Iteration   1: 3.582 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.582 ops/ms


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
# Warmup Iteration   1: 5.608 ±(99.9%) 0.077 ms/op
Iteration   1: 3.033 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.033 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.036 ms/op
Iteration   1: 1.891 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.891 ms/op


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.061 ms/op
Iteration   1: 3.398 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.398 ms/op


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
# Warmup Iteration   1: 12.910 ±(99.9%) 0.273 ms/op
Iteration   1: 9.163 ±(99.9%) 0.138 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.163 ms/op


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.099 ms/op
Iteration   1: 3.308 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.797 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9668
  mean =      3.308 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 999 
    [ 2.500,  5.000) = 8236 
    [ 5.000,  7.500) = 253 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.797 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.009 ±(99.9%) 0.071 ms/op
Iteration   1: 1.892 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   5.942 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 15.803 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16914
  mean =      1.892 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 653 
    [ 1.250,  2.500) = 15035 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      5.942 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     15.803 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ±(99.9%) 0.096 ms/op
Iteration   1: 2.882 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.724 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   4.742 ms/op
                 getUser·p0.999:  6.484 ms/op
                 getUser·p0.9999: 9.263 ms/op
                 getUser·p1.00:   9.486 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11208
  mean =      2.882 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 362 
    [ 2.000,  3.000) = 6933 
    [ 3.000,  4.000) = 3083 
    [ 4.000,  5.000) = 741 
    [ 5.000,  6.000) = 47 
    [ 6.000,  7.000) = 30 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      4.742 ms/op
     p(99.9000) =      6.484 ms/op
     p(99.9900) =      9.263 ms/op
     p(99.9990) =      9.486 ms/op
     p(99.9999) =      9.486 ms/op
    p(100.0000) =      9.486 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.667 ±(99.9%) 0.411 ms/op
Iteration   1: 7.736 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   2.863 ms/op
                 listUser·p0.50:   7.332 ms/op
                 listUser·p0.90:   9.814 ms/op
                 listUser·p0.95:   11.256 ms/op
                 listUser·p0.99:   20.482 ms/op
                 listUser·p0.999:  28.569 ms/op
                 listUser·p0.9999: 38.535 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4138
  mean =      7.736 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 162 
    [ 5.000,  7.500) = 2103 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.863 ms/op
     p(50.0000) =      7.332 ms/op
     p(90.0000) =      9.814 ms/op
     p(95.0000) =     11.256 ms/op
     p(99.0000) =     20.482 ms/op
     p(99.9000) =     28.569 ms/op
     p(99.9900) =     38.535 ms/op
     p(99.9990) =     38.535 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.458          ops/ms
Client.existUser                       thrpt         14.679          ops/ms
Client.getUser                         thrpt          8.523          ops/ms
Client.listUser                        thrpt          3.582          ops/ms
Client.createUser                       avgt          3.033           ms/op
Client.existUser                        avgt          1.891           ms/op
Client.getUser                          avgt          3.398           ms/op
Client.listUser                         avgt          9.163           ms/op
Client.createUser                     sample   9668   3.308 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.071           ms/op
Client.createUser:createUser·p0.50    sample          3.076           ms/op
Client.createUser:createUser·p0.90    sample          3.912           ms/op
Client.createUser:createUser·p0.95    sample          4.797           ms/op
Client.createUser:createUser·p0.99    sample          9.585           ms/op
Client.createUser:createUser·p0.999   sample         19.956           ms/op
Client.createUser:createUser·p0.9999  sample         20.480           ms/op
Client.createUser:createUser·p1.00    sample         20.480           ms/op
Client.existUser                      sample  16914   1.892 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.570           ms/op
Client.existUser:existUser·p0.50      sample          1.745           ms/op
Client.existUser:existUser·p0.90      sample          2.363           ms/op
Client.existUser:existUser·p0.95      sample          2.626           ms/op
Client.existUser:existUser·p0.99      sample          5.942           ms/op
Client.existUser:existUser·p0.999     sample         13.926           ms/op
Client.existUser:existUser·p0.9999    sample         15.803           ms/op
Client.existUser:existUser·p1.00      sample         18.907           ms/op
Client.getUser                        sample  11208   2.882 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.679           ms/op
Client.getUser:getUser·p0.50          sample          2.724           ms/op
Client.getUser:getUser·p0.90          sample          3.817           ms/op
Client.getUser:getUser·p0.95          sample          4.166           ms/op
Client.getUser:getUser·p0.99          sample          4.742           ms/op
Client.getUser:getUser·p0.999         sample          6.484           ms/op
Client.getUser:getUser·p0.9999        sample          9.263           ms/op
Client.getUser:getUser·p1.00          sample          9.486           ms/op
Client.listUser                       sample   4138   7.736 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          2.863           ms/op
Client.listUser:listUser·p0.50        sample          7.332           ms/op
Client.listUser:listUser·p0.90        sample          9.814           ms/op
Client.listUser:listUser·p0.95        sample         11.256           ms/op
Client.listUser:listUser·p0.99        sample         20.482           ms/op
Client.listUser:listUser·p0.999       sample         28.569           ms/op
Client.listUser:listUser·p0.9999      sample         38.535           ms/op
Client.listUser:listUser·p1.00        sample         38.535           ms/op
