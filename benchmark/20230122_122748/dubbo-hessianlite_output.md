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
# Warmup Iteration   1: 1.021 ops/ms
Iteration   1: 3.174 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.174 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ops/ms
Iteration   1: 8.694 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.694 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.498 ops/ms
Iteration   1: 5.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.352 ops/ms


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
# Warmup Iteration   1: 0.958 ops/ms
Iteration   1: 1.308 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.308 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.986 ±(99.9%) 0.325 ms/op
Iteration   1: 7.997 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.997 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.858 ±(99.9%) 0.067 ms/op
Iteration   1: 4.306 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.306 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.070 ±(99.9%) 0.138 ms/op
Iteration   1: 4.619 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.619 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.409 ±(99.9%) 0.461 ms/op
Iteration   1: 15.649 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.649 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.104 ±(99.9%) 0.267 ms/op
Iteration   1: 6.341 ±(99.9%) 0.140 ms/op
                 createUser·p0.00:   2.912 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   6.414 ms/op
                 createUser·p0.95:   9.617 ms/op
                 createUser·p0.99:   25.166 ms/op
                 createUser·p0.999:  28.508 ms/op
                 createUser·p0.9999: 28.541 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5126
  mean =      6.341 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 31 
    [ 5.000,  7.500) = 4700 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.912 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      9.617 ms/op
     p(99.0000) =     25.166 ms/op
     p(99.9000) =     28.508 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 6.889 ±(99.9%) 0.267 ms/op
Iteration   1: 3.607 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.298 ms/op
                 existUser·p0.99:   13.375 ms/op
                 existUser·p0.999:  16.501 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8866
  mean =      3.607 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 273 
    [ 2.500,  3.750) = 7120 
    [ 3.750,  5.000) = 1215 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.298 ms/op
     p(99.0000) =     13.375 ms/op
     p(99.9000) =     16.501 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 9.041 ±(99.9%) 0.354 ms/op
Iteration   1: 4.071 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  20.644 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7852
  mean =      4.071 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 7197 
    [ 5.000,  7.500) = 606 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.322 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     20.644 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.185 ±(99.9%) 1.316 ms/op
Iteration   1: 18.372 ±(99.9%) 0.259 ms/op
                 listUser·p0.00:   8.716 ms/op
                 listUser·p0.50:   17.826 ms/op
                 listUser·p0.90:   21.332 ms/op
                 listUser·p0.95:   25.074 ms/op
                 listUser·p0.99:   28.377 ms/op
                 listUser·p0.999:  29.279 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1755
  mean =     18.372 ±(99.9%) 0.259 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 633 
    [17.500, 20.000) = 403 
    [20.000, 22.500) = 423 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      8.716 ms/op
     p(50.0000) =     17.826 ms/op
     p(90.0000) =     21.332 ms/op
     p(95.0000) =     25.074 ms/op
     p(99.0000) =     28.377 ms/op
     p(99.9000) =     29.279 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.174          ops/ms
Client.existUser                       thrpt         8.694          ops/ms
Client.getUser                         thrpt         5.352          ops/ms
Client.listUser                        thrpt         1.308          ops/ms
Client.createUser                       avgt         7.997           ms/op
Client.existUser                        avgt         4.306           ms/op
Client.getUser                          avgt         4.619           ms/op
Client.listUser                         avgt        15.649           ms/op
Client.createUser                     sample  5126   6.341 ± 0.140   ms/op
Client.createUser:createUser·p0.00    sample         2.912           ms/op
Client.createUser:createUser·p0.50    sample         5.661           ms/op
Client.createUser:createUser·p0.90    sample         6.414           ms/op
Client.createUser:createUser·p0.95    sample         9.617           ms/op
Client.createUser:createUser·p0.99    sample        25.166           ms/op
Client.createUser:createUser·p0.999   sample        28.508           ms/op
Client.createUser:createUser·p0.9999  sample        28.541           ms/op
Client.createUser:createUser·p1.00    sample        28.541           ms/op
Client.existUser                      sample  8866   3.607 ± 0.052   ms/op
Client.existUser:existUser·p0.00      sample         1.290           ms/op
Client.existUser:existUser·p0.50      sample         3.453           ms/op
Client.existUser:existUser·p0.90      sample         3.998           ms/op
Client.existUser:existUser·p0.95      sample         4.298           ms/op
Client.existUser:existUser·p0.99      sample        13.375           ms/op
Client.existUser:existUser·p0.999     sample        16.501           ms/op
Client.existUser:existUser·p0.9999    sample        17.367           ms/op
Client.existUser:existUser·p1.00      sample        17.367           ms/op
Client.getUser                        sample  7852   4.071 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample         2.322           ms/op
Client.getUser:getUser·p0.50          sample         3.879           ms/op
Client.getUser:getUser·p0.90          sample         4.882           ms/op
Client.getUser:getUser·p0.95          sample         5.235           ms/op
Client.getUser:getUser·p0.99          sample         6.136           ms/op
Client.getUser:getUser·p0.999         sample        20.644           ms/op
Client.getUser:getUser·p0.9999        sample        20.709           ms/op
Client.getUser:getUser·p1.00          sample        20.709           ms/op
Client.listUser                       sample  1755  18.372 ± 0.259   ms/op
Client.listUser:listUser·p0.00        sample         8.716           ms/op
Client.listUser:listUser·p0.50        sample        17.826           ms/op
Client.listUser:listUser·p0.90        sample        21.332           ms/op
Client.listUser:listUser·p0.95        sample        25.074           ms/op
Client.listUser:listUser·p0.99        sample        28.377           ms/op
Client.listUser:listUser·p0.999       sample        29.279           ms/op
Client.listUser:listUser·p0.9999      sample        30.245           ms/op
Client.listUser:listUser·p1.00        sample        30.245           ms/op
