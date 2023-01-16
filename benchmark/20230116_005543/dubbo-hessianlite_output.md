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
# Warmup Iteration   1: 1.241 ops/ms
Iteration   1: 2.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.671 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.623 ops/ms
Iteration   1: 6.628 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.628 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 5.122 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.122 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.910 ops/ms
Iteration   1: 1.298 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.298 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.757 ±(99.9%) 0.145 ms/op
Iteration   1: 6.803 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.803 ms/op


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
# Warmup Iteration   1: 6.995 ±(99.9%) 0.074 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.758 ms/op


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
# Warmup Iteration   1: 9.424 ±(99.9%) 0.138 ms/op
Iteration   1: 4.910 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.910 ms/op


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
# Warmup Iteration   1: 28.008 ±(99.9%) 0.353 ms/op
Iteration   1: 18.195 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.195 ms/op


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
# Warmup Iteration   1: 10.310 ±(99.9%) 0.326 ms/op
Iteration   1: 6.454 ±(99.9%) 0.173 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   10.289 ms/op
                 createUser·p0.95:   13.386 ms/op
                 createUser·p0.99:   21.692 ms/op
                 createUser·p0.999:  38.732 ms/op
                 createUser·p0.9999: 38.732 ms/op
                 createUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5042
  mean =      6.454 ±(99.9%) 0.173 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 1954 
    [ 5.000,  7.500) = 2393 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =     10.289 ms/op
     p(95.0000) =     13.386 ms/op
     p(99.0000) =     21.692 ms/op
     p(99.9000) =     38.732 ms/op
     p(99.9900) =     38.732 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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
# Warmup Iteration   1: 6.022 ±(99.9%) 0.311 ms/op
Iteration   1: 3.422 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.033 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.391 ms/op
                 existUser·p0.999:  14.560 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9340
  mean =      3.422 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1426 
    [ 2.500,  3.750) = 4558 
    [ 3.750,  5.000) = 3115 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.033 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.391 ms/op
     p(99.9000) =     14.560 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 8.962 ±(99.9%) 0.302 ms/op
Iteration   1: 4.556 ±(99.9%) 0.060 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.724 ms/op
                 getUser·p0.95:   6.554 ms/op
                 getUser·p0.99:   11.693 ms/op
                 getUser·p0.999:  16.301 ms/op
                 getUser·p0.9999: 16.433 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7032
  mean =      4.556 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 62 
    [ 2.500,  3.750) = 2160 
    [ 3.750,  5.000) = 2184 
    [ 5.000,  6.250) = 2223 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.724 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =     11.693 ms/op
     p(99.9000) =     16.301 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.286 ±(99.9%) 0.845 ms/op
Iteration   1: 16.908 ±(99.9%) 0.277 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   16.368 ms/op
                 listUser·p0.90:   20.152 ms/op
                 listUser·p0.95:   23.069 ms/op
                 listUser·p0.99:   35.117 ms/op
                 listUser·p0.999:  38.674 ms/op
                 listUser·p0.9999: 38.732 ms/op
                 listUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1887
  mean =     16.908 ±(99.9%) 0.277 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 13 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 1160 
    [17.500, 20.000) = 286 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.671 ms/op
     p(50.0000) =     16.368 ms/op
     p(90.0000) =     20.152 ms/op
     p(95.0000) =     23.069 ms/op
     p(99.0000) =     35.117 ms/op
     p(99.9000) =     38.674 ms/op
     p(99.9900) =     38.732 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.671          ops/ms
Client.existUser                       thrpt         6.628          ops/ms
Client.getUser                         thrpt         5.122          ops/ms
Client.listUser                        thrpt         1.298          ops/ms
Client.createUser                       avgt         6.803           ms/op
Client.existUser                        avgt         3.758           ms/op
Client.getUser                          avgt         4.910           ms/op
Client.listUser                         avgt        18.195           ms/op
Client.createUser                     sample  5042   6.454 ± 0.173   ms/op
Client.createUser:createUser·p0.00    sample         2.306           ms/op
Client.createUser:createUser·p0.50    sample         5.595           ms/op
Client.createUser:createUser·p0.90    sample        10.289           ms/op
Client.createUser:createUser·p0.95    sample        13.386           ms/op
Client.createUser:createUser·p0.99    sample        21.692           ms/op
Client.createUser:createUser·p0.999   sample        38.732           ms/op
Client.createUser:createUser·p0.9999  sample        38.732           ms/op
Client.createUser:createUser·p1.00    sample        38.732           ms/op
Client.existUser                      sample  9340   3.422 ± 0.038   ms/op
Client.existUser:existUser·p0.00      sample         1.061           ms/op
Client.existUser:existUser·p0.50      sample         3.033           ms/op
Client.existUser:existUser·p0.90      sample         4.407           ms/op
Client.existUser:existUser·p0.95      sample         4.596           ms/op
Client.existUser:existUser·p0.99      sample         7.391           ms/op
Client.existUser:existUser·p0.999     sample        14.560           ms/op
Client.existUser:existUser·p0.9999    sample        14.582           ms/op
Client.existUser:existUser·p1.00      sample        14.582           ms/op
Client.getUser                        sample  7032   4.556 ± 0.060   ms/op
Client.getUser:getUser·p0.00          sample         1.294           ms/op
Client.getUser:getUser·p0.50          sample         4.465           ms/op
Client.getUser:getUser·p0.90          sample         5.724           ms/op
Client.getUser:getUser·p0.95          sample         6.554           ms/op
Client.getUser:getUser·p0.99          sample        11.693           ms/op
Client.getUser:getUser·p0.999         sample        16.301           ms/op
Client.getUser:getUser·p0.9999        sample        16.433           ms/op
Client.getUser:getUser·p1.00          sample        16.433           ms/op
Client.listUser                       sample  1887  16.908 ± 0.277   ms/op
Client.listUser:listUser·p0.00        sample         2.671           ms/op
Client.listUser:listUser·p0.50        sample        16.368           ms/op
Client.listUser:listUser·p0.90        sample        20.152           ms/op
Client.listUser:listUser·p0.95        sample        23.069           ms/op
Client.listUser:listUser·p0.99        sample        35.117           ms/op
Client.listUser:listUser·p0.999       sample        38.674           ms/op
Client.listUser:listUser·p0.9999      sample        38.732           ms/op
Client.listUser:listUser·p1.00        sample        38.732           ms/op
