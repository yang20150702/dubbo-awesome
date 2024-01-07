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
# Warmup Iteration   1: 2.473 ops/ms
Iteration   1: 5.570 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.570 ops/ms


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
# Warmup Iteration   1: 5.973 ops/ms
Iteration   1: 13.224 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.224 ops/ms


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
# Warmup Iteration   1: 3.517 ops/ms
Iteration   1: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.029 ops/ms


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
# Warmup Iteration   1: 2.245 ops/ms
Iteration   1: 3.511 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.511 ops/ms


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
# Warmup Iteration   1: 5.765 ±(99.9%) 0.078 ms/op
Iteration   1: 3.442 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.442 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.030 ms/op
Iteration   1: 1.722 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.722 ms/op


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
# Warmup Iteration   1: 5.835 ±(99.9%) 0.072 ms/op
Iteration   1: 3.194 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.194 ms/op


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
# Warmup Iteration   1: 11.017 ±(99.9%) 0.181 ms/op
Iteration   1: 8.954 ±(99.9%) 0.118 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.954 ms/op


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
# Warmup Iteration   1: 5.301 ±(99.9%) 0.130 ms/op
Iteration   1: 2.905 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.996 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 16.438 ms/op
                 createUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11225
  mean =      2.905 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2607 
    [ 2.500,  3.750) = 7951 
    [ 3.750,  5.000) = 315 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.996 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     16.438 ms/op
     p(99.9990) =     16.499 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.057 ms/op
Iteration   1: 1.946 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.638 ms/op
                 existUser·p0.95:   2.859 ms/op
                 existUser·p0.99:   3.235 ms/op
                 existUser·p0.999:  21.777 ms/op
                 existUser·p0.9999: 22.809 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16428
  mean =      1.946 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14020 
    [ 2.500,  5.000) = 2362 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.235 ms/op
     p(99.9000) =     21.777 ms/op
     p(99.9900) =     22.809 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.120 ms/op
Iteration   1: 2.889 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.757 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.999 ms/op
                 getUser·p0.99:   4.680 ms/op
                 getUser·p0.999:  6.553 ms/op
                 getUser·p0.9999: 7.263 ms/op
                 getUser·p1.00:   7.283 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11071
  mean =      2.889 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 47 
    [1.500, 2.000) = 392 
    [2.000, 2.500) = 2701 
    [2.500, 3.000) = 3804 
    [3.000, 3.500) = 2409 
    [3.500, 4.000) = 1164 
    [4.000, 4.500) = 393 
    [4.500, 5.000) = 77 
    [5.000, 5.500) = 24 
    [5.500, 6.000) = 27 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 12 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.999 ms/op
     p(99.0000) =      4.680 ms/op
     p(99.9000) =      6.553 ms/op
     p(99.9900) =      7.263 ms/op
     p(99.9990) =      7.283 ms/op
     p(99.9999) =      7.283 ms/op
    p(100.0000) =      7.283 ms/op


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
# Warmup Iteration   1: 11.395 ±(99.9%) 0.386 ms/op
Iteration   1: 7.461 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   7.213 ms/op
                 listUser·p0.90:   9.486 ms/op
                 listUser·p0.95:   10.650 ms/op
                 listUser·p0.99:   14.967 ms/op
                 listUser·p0.999:  20.641 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4280
  mean =      7.461 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 203 
    [ 5.000,  7.500) = 2287 
    [ 7.500, 10.000) = 1486 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.855 ms/op
     p(50.0000) =      7.213 ms/op
     p(90.0000) =      9.486 ms/op
     p(95.0000) =     10.650 ms/op
     p(99.0000) =     14.967 ms/op
     p(99.9000) =     20.641 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.570          ops/ms
Client.existUser                       thrpt         13.224          ops/ms
Client.getUser                         thrpt          8.029          ops/ms
Client.listUser                        thrpt          3.511          ops/ms
Client.createUser                       avgt          3.442           ms/op
Client.existUser                        avgt          1.722           ms/op
Client.getUser                          avgt          3.194           ms/op
Client.listUser                         avgt          8.954           ms/op
Client.createUser                     sample  11225   2.905 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.020           ms/op
Client.createUser:createUser·p0.50    sample          2.728           ms/op
Client.createUser:createUser·p0.90    sample          3.449           ms/op
Client.createUser:createUser·p0.95    sample          3.996           ms/op
Client.createUser:createUser·p0.99    sample          6.865           ms/op
Client.createUser:createUser·p0.999   sample         13.992           ms/op
Client.createUser:createUser·p0.9999  sample         16.438           ms/op
Client.createUser:createUser·p1.00    sample         16.499           ms/op
Client.existUser                      sample  16428   1.946 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.664           ms/op
Client.existUser:existUser·p0.50      sample          1.745           ms/op
Client.existUser:existUser·p0.90      sample          2.638           ms/op
Client.existUser:existUser·p0.95      sample          2.859           ms/op
Client.existUser:existUser·p0.99      sample          3.235           ms/op
Client.existUser:existUser·p0.999     sample         21.777           ms/op
Client.existUser:existUser·p0.9999    sample         22.809           ms/op
Client.existUser:existUser·p1.00      sample         22.872           ms/op
Client.getUser                        sample  11071   2.889 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.945           ms/op
Client.getUser:getUser·p0.50          sample          2.757           ms/op
Client.getUser:getUser·p0.90          sample          3.703           ms/op
Client.getUser:getUser·p0.95          sample          3.999           ms/op
Client.getUser:getUser·p0.99          sample          4.680           ms/op
Client.getUser:getUser·p0.999         sample          6.553           ms/op
Client.getUser:getUser·p0.9999        sample          7.263           ms/op
Client.getUser:getUser·p1.00          sample          7.283           ms/op
Client.listUser                       sample   4280   7.461 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          2.855           ms/op
Client.listUser:listUser·p0.50        sample          7.213           ms/op
Client.listUser:listUser·p0.90        sample          9.486           ms/op
Client.listUser:listUser·p0.95        sample         10.650           ms/op
Client.listUser:listUser·p0.99        sample         14.967           ms/op
Client.listUser:listUser·p0.999       sample         20.641           ms/op
Client.listUser:listUser·p0.9999      sample         22.479           ms/op
Client.listUser:listUser·p1.00        sample         22.479           ms/op
