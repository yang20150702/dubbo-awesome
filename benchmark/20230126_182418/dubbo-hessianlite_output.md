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
# Warmup Iteration   1: 1.163 ops/ms
Iteration   1: 3.309 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.309 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ops/ms
Iteration   1: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.959 ops/ms


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
# Warmup Iteration   1: 2.851 ops/ms
Iteration   1: 6.719 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.719 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.970 ops/ms
Iteration   1: 1.327 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.327 ops/ms


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
# Warmup Iteration   1: 13.300 ±(99.9%) 0.141 ms/op
Iteration   1: 5.980 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.980 ms/op


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
# Warmup Iteration   1: 6.737 ±(99.9%) 0.090 ms/op
Iteration   1: 2.734 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.734 ms/op


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
# Warmup Iteration   1: 8.506 ±(99.9%) 0.119 ms/op
Iteration   1: 4.572 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.572 ms/op


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
# Warmup Iteration   1: 31.430 ±(99.9%) 0.537 ms/op
Iteration   1: 19.356 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.356 ms/op


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
# Warmup Iteration   1: 9.500 ±(99.9%) 0.328 ms/op
Iteration   1: 5.762 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   12.062 ms/op
                 createUser·p0.99:   17.891 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5555
  mean =      5.762 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 1517 
    [ 5.000,  7.500) = 3713 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =     12.062 ms/op
     p(99.0000) =     17.891 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.771 ±(99.9%) 0.195 ms/op
Iteration   1: 2.980 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.679 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   4.090 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  20.087 ms/op
                 existUser·p0.9999: 20.832 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10849
  mean =      2.980 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3426 
    [ 2.500,  5.000) = 6987 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      4.090 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     20.832 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 7.508 ±(99.9%) 0.234 ms/op
Iteration   1: 4.367 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  12.777 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7390
  mean =      4.367 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 221 
    [ 2.500,  3.750) = 1956 
    [ 3.750,  5.000) = 3864 
    [ 5.000,  6.250) = 1000 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     12.777 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 24.639 ±(99.9%) 0.560 ms/op
Iteration   1: 16.418 ±(99.9%) 0.200 ms/op
                 listUser·p0.00:   7.037 ms/op
                 listUser·p0.50:   16.187 ms/op
                 listUser·p0.90:   18.579 ms/op
                 listUser·p0.95:   20.480 ms/op
                 listUser·p0.99:   26.543 ms/op
                 listUser·p0.999:  30.071 ms/op
                 listUser·p0.9999: 31.654 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1965
  mean =     16.418 ±(99.9%) 0.200 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 1129 
    [17.500, 20.000) = 349 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.037 ms/op
     p(50.0000) =     16.187 ms/op
     p(90.0000) =     18.579 ms/op
     p(95.0000) =     20.480 ms/op
     p(99.0000) =     26.543 ms/op
     p(99.9000) =     30.071 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.309          ops/ms
Client.existUser                       thrpt          7.959          ops/ms
Client.getUser                         thrpt          6.719          ops/ms
Client.listUser                        thrpt          1.327          ops/ms
Client.createUser                       avgt          5.980           ms/op
Client.existUser                        avgt          2.734           ms/op
Client.getUser                          avgt          4.572           ms/op
Client.listUser                         avgt         19.356           ms/op
Client.createUser                     sample   5555   5.762 ± 0.110   ms/op
Client.createUser:createUser·p0.00    sample          2.097           ms/op
Client.createUser:createUser·p0.50    sample          5.292           ms/op
Client.createUser:createUser·p0.90    sample          5.964           ms/op
Client.createUser:createUser·p0.95    sample         12.062           ms/op
Client.createUser:createUser·p0.99    sample         17.891           ms/op
Client.createUser:createUser·p0.999   sample         20.414           ms/op
Client.createUser:createUser·p0.9999  sample         23.298           ms/op
Client.createUser:createUser·p1.00    sample         23.298           ms/op
Client.existUser                      sample  10849   2.980 ± 0.048   ms/op
Client.existUser:existUser·p0.00      sample          0.865           ms/op
Client.existUser:existUser·p0.50      sample          2.679           ms/op
Client.existUser:existUser·p0.90      sample          3.461           ms/op
Client.existUser:existUser·p0.95      sample          4.090           ms/op
Client.existUser:existUser·p0.99      sample          9.716           ms/op
Client.existUser:existUser·p0.999     sample         20.087           ms/op
Client.existUser:existUser·p0.9999    sample         20.832           ms/op
Client.existUser:existUser·p1.00      sample         20.840           ms/op
Client.getUser                        sample   7390   4.367 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          1.157           ms/op
Client.getUser:getUser·p0.50          sample          4.342           ms/op
Client.getUser:getUser·p0.90          sample          5.317           ms/op
Client.getUser:getUser·p0.95          sample          6.095           ms/op
Client.getUser:getUser·p0.99          sample         10.650           ms/op
Client.getUser:getUser·p0.999         sample         12.777           ms/op
Client.getUser:getUser·p0.9999        sample         13.861           ms/op
Client.getUser:getUser·p1.00          sample         13.861           ms/op
Client.listUser                       sample   1965  16.418 ± 0.200   ms/op
Client.listUser:listUser·p0.00        sample          7.037           ms/op
Client.listUser:listUser·p0.50        sample         16.187           ms/op
Client.listUser:listUser·p0.90        sample         18.579           ms/op
Client.listUser:listUser·p0.95        sample         20.480           ms/op
Client.listUser:listUser·p0.99        sample         26.543           ms/op
Client.listUser:listUser·p0.999       sample         30.071           ms/op
Client.listUser:listUser·p0.9999      sample         31.654           ms/op
Client.listUser:listUser·p1.00        sample         31.654           ms/op
