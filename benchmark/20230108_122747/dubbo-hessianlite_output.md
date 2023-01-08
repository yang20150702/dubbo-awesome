# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.062 ops/ms
Iteration   1: 2.409 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.409 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
Iteration   1: 6.056 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.056 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
Iteration   1: 5.952 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.952 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.891 ops/ms
Iteration   1: 1.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.576 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 12.369 ±(99.9%) 0.210 ms/op
Iteration   1: 7.215 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.215 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.613 ±(99.9%) 0.065 ms/op
Iteration   1: 3.807 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.807 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.452 ±(99.9%) 0.126 ms/op
Iteration   1: 5.219 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.219 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 23.840 ±(99.9%) 0.364 ms/op
Iteration   1: 12.671 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  12.671 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.744 ±(99.9%) 0.326 ms/op
Iteration   1: 6.156 ±(99.9%) 0.113 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   5.833 ms/op
                 createUser·p0.90:   7.545 ms/op
                 createUser·p0.95:   10.977 ms/op
                 createUser·p0.99:   15.752 ms/op
                 createUser·p0.999:  25.287 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5256
  mean =      6.156 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 384 
    [ 5.000,  7.500) = 4125 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      5.833 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =     10.977 ms/op
     p(99.0000) =     15.752 ms/op
     p(99.9000) =     25.287 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ±(99.9%) 0.223 ms/op
Iteration   1: 3.413 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.427 ms/op
                 existUser·p0.999:  16.038 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9381
  mean =      3.413 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 1759 
    [ 2.500,  3.750) = 4529 
    [ 3.750,  5.000) = 2846 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.427 ms/op
     p(99.9000) =     16.038 ms/op
     p(99.9900) =     16.433 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.808 ±(99.9%) 0.461 ms/op
Iteration   1: 3.757 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.414 ms/op
                 getUser·p0.99:   9.208 ms/op
                 getUser·p0.999:  17.703 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8510
  mean =      3.757 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 506 
    [ 2.500,  3.750) = 4235 
    [ 3.750,  5.000) = 3200 
    [ 5.000,  6.250) = 228 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.414 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     17.703 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.625 ±(99.9%) 0.808 ms/op
Iteration   1: 16.270 ±(99.9%) 0.235 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   15.696 ms/op
                 listUser·p0.90:   18.514 ms/op
                 listUser·p0.95:   19.759 ms/op
                 listUser·p0.99:   32.233 ms/op
                 listUser·p0.999:  38.149 ms/op
                 listUser·p0.9999: 38.339 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1961
  mean =     16.270 ±(99.9%) 0.235 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 587 
    [15.000, 17.500) = 820 
    [17.500, 20.000) = 395 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.445 ms/op
     p(50.0000) =     15.696 ms/op
     p(90.0000) =     18.514 ms/op
     p(95.0000) =     19.759 ms/op
     p(99.0000) =     32.233 ms/op
     p(99.9000) =     38.149 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.409          ops/ms
Client.existUser                       thrpt         6.056          ops/ms
Client.getUser                         thrpt         5.952          ops/ms
Client.listUser                        thrpt         1.576          ops/ms
Client.createUser                       avgt         7.215           ms/op
Client.existUser                        avgt         3.807           ms/op
Client.getUser                          avgt         5.219           ms/op
Client.listUser                         avgt        12.671           ms/op
Client.createUser                     sample  5256   6.156 ± 0.113   ms/op
Client.createUser:createUser·p0.00    sample         1.524           ms/op
Client.createUser:createUser·p0.50    sample         5.833           ms/op
Client.createUser:createUser·p0.90    sample         7.545           ms/op
Client.createUser:createUser·p0.95    sample        10.977           ms/op
Client.createUser:createUser·p0.99    sample        15.752           ms/op
Client.createUser:createUser·p0.999   sample        25.287           ms/op
Client.createUser:createUser·p0.9999  sample        26.313           ms/op
Client.createUser:createUser·p1.00    sample        26.313           ms/op
Client.existUser                      sample  9381   3.413 ± 0.038   ms/op
Client.existUser:existUser·p0.00      sample         0.821           ms/op
Client.existUser:existUser·p0.50      sample         3.572           ms/op
Client.existUser:existUser·p0.90      sample         3.990           ms/op
Client.existUser:existUser·p0.95      sample         4.133           ms/op
Client.existUser:existUser·p0.99      sample         6.427           ms/op
Client.existUser:existUser·p0.999     sample        16.038           ms/op
Client.existUser:existUser·p0.9999    sample        16.433           ms/op
Client.existUser:existUser·p1.00      sample        16.433           ms/op
Client.getUser                        sample  8510   3.757 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample         1.169           ms/op
Client.getUser:getUser·p0.50          sample         3.535           ms/op
Client.getUser:getUser·p0.90          sample         4.588           ms/op
Client.getUser:getUser·p0.95          sample         5.414           ms/op
Client.getUser:getUser·p0.99          sample         9.208           ms/op
Client.getUser:getUser·p0.999         sample        17.703           ms/op
Client.getUser:getUser·p0.9999        sample        19.005           ms/op
Client.getUser:getUser·p1.00          sample        19.005           ms/op
Client.listUser                       sample  1961  16.270 ± 0.235   ms/op
Client.listUser:listUser·p0.00        sample         2.445           ms/op
Client.listUser:listUser·p0.50        sample        15.696           ms/op
Client.listUser:listUser·p0.90        sample        18.514           ms/op
Client.listUser:listUser·p0.95        sample        19.759           ms/op
Client.listUser:listUser·p0.99        sample        32.233           ms/op
Client.listUser:listUser·p0.999       sample        38.149           ms/op
Client.listUser:listUser·p0.9999      sample        38.339           ms/op
Client.listUser:listUser·p1.00        sample        38.339           ms/op
