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
# Warmup Iteration   1: 1.204 ops/ms
Iteration   1: 2.968 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.968 ops/ms


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
# Warmup Iteration   1: 3.485 ops/ms
Iteration   1: 7.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.732 ops/ms


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
# Warmup Iteration   1: 2.343 ops/ms
Iteration   1: 5.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.379 ops/ms


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
# Warmup Iteration   1: 1.013 ops/ms
Iteration   1: 1.658 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.658 ops/ms


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
# Warmup Iteration   1: 14.235 ±(99.9%) 0.281 ms/op
Iteration   1: 8.060 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.060 ms/op


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
# Warmup Iteration   1: 7.757 ±(99.9%) 0.109 ms/op
Iteration   1: 4.168 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.168 ms/op


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
# Warmup Iteration   1: 7.267 ±(99.9%) 0.068 ms/op
Iteration   1: 4.814 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.814 ms/op


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
# Warmup Iteration   1: 24.025 ±(99.9%) 0.336 ms/op
Iteration   1: 17.612 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.612 ms/op


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
# Warmup Iteration   1: 8.944 ±(99.9%) 0.354 ms/op
Iteration   1: 6.176 ±(99.9%) 0.131 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   5.685 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   9.945 ms/op
                 createUser·p0.99:   17.259 ms/op
                 createUser·p0.999:  35.702 ms/op
                 createUser·p0.9999: 35.979 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5230
  mean =      6.176 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 245 
    [ 5.000,  7.500) = 4577 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     17.259 ms/op
     p(99.9000) =     35.702 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 7.212 ±(99.9%) 0.185 ms/op
Iteration   1: 3.247 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  15.962 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9872
  mean =      3.247 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 134 
    [ 2.500,  3.750) = 9376 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     15.962 ms/op
     p(99.9900) =     16.433 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 9.947 ±(99.9%) 0.311 ms/op
Iteration   1: 4.249 ±(99.9%) 0.055 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   9.454 ms/op
                 getUser·p0.999:  22.358 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7565
  mean =      4.249 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 6696 
    [ 5.000,  7.500) = 557 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     22.358 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 29.168 ±(99.9%) 0.901 ms/op
Iteration   1: 17.123 ±(99.9%) 0.228 ms/op
                 listUser·p0.00:   7.856 ms/op
                 listUser·p0.50:   16.843 ms/op
                 listUser·p0.90:   20.185 ms/op
                 listUser·p0.95:   23.113 ms/op
                 listUser·p0.99:   25.924 ms/op
                 listUser·p0.999:  33.024 ms/op
                 listUser·p0.9999: 34.341 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1892
  mean =     17.123 ±(99.9%) 0.228 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 382 
    [15.000, 17.500) = 642 
    [17.500, 20.000) = 614 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.856 ms/op
     p(50.0000) =     16.843 ms/op
     p(90.0000) =     20.185 ms/op
     p(95.0000) =     23.113 ms/op
     p(99.0000) =     25.924 ms/op
     p(99.9000) =     33.024 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.968          ops/ms
Client.existUser                       thrpt         7.732          ops/ms
Client.getUser                         thrpt         5.379          ops/ms
Client.listUser                        thrpt         1.658          ops/ms
Client.createUser                       avgt         8.060           ms/op
Client.existUser                        avgt         4.168           ms/op
Client.getUser                          avgt         4.814           ms/op
Client.listUser                         avgt        17.612           ms/op
Client.createUser                     sample  5230   6.176 ± 0.131   ms/op
Client.createUser:createUser·p0.00    sample         1.714           ms/op
Client.createUser:createUser·p0.50    sample         5.685           ms/op
Client.createUser:createUser·p0.90    sample         6.406           ms/op
Client.createUser:createUser·p0.95    sample         9.945           ms/op
Client.createUser:createUser·p0.99    sample        17.259           ms/op
Client.createUser:createUser·p0.999   sample        35.702           ms/op
Client.createUser:createUser·p0.9999  sample        35.979           ms/op
Client.createUser:createUser·p1.00    sample        35.979           ms/op
Client.existUser                      sample  9872   3.247 ± 0.039   ms/op
Client.existUser:existUser·p0.00      sample         0.766           ms/op
Client.existUser:existUser·p0.50      sample         3.056           ms/op
Client.existUser:existUser·p0.90      sample         3.428           ms/op
Client.existUser:existUser·p0.95      sample         3.523           ms/op
Client.existUser:existUser·p0.99      sample        10.289           ms/op
Client.existUser:existUser·p0.999     sample        15.962           ms/op
Client.existUser:existUser·p0.9999    sample        16.433           ms/op
Client.existUser:existUser·p1.00      sample        16.433           ms/op
Client.getUser                        sample  7565   4.249 ± 0.055   ms/op
Client.getUser:getUser·p0.00          sample         1.039           ms/op
Client.getUser:getUser·p0.50          sample         4.133           ms/op
Client.getUser:getUser·p0.90          sample         4.948           ms/op
Client.getUser:getUser·p0.95          sample         5.358           ms/op
Client.getUser:getUser·p0.99          sample         9.454           ms/op
Client.getUser:getUser·p0.999         sample        22.358           ms/op
Client.getUser:getUser·p0.9999        sample        23.003           ms/op
Client.getUser:getUser·p1.00          sample        23.003           ms/op
Client.listUser                       sample  1892  17.123 ± 0.228   ms/op
Client.listUser:listUser·p0.00        sample         7.856           ms/op
Client.listUser:listUser·p0.50        sample        16.843           ms/op
Client.listUser:listUser·p0.90        sample        20.185           ms/op
Client.listUser:listUser·p0.95        sample        23.113           ms/op
Client.listUser:listUser·p0.99        sample        25.924           ms/op
Client.listUser:listUser·p0.999       sample        33.024           ms/op
Client.listUser:listUser·p0.9999      sample        34.341           ms/op
Client.listUser:listUser·p1.00        sample        34.341           ms/op
