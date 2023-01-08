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
# Warmup Iteration   1: 0.580 ops/ms
Iteration   1: 1.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.112 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
Iteration   1: 3.953 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.953 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.168 ops/ms
Iteration   1: 2.480 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.480 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.648 ops/ms
Iteration   1: 0.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.864 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 29.661 ±(99.9%) 0.797 ms/op
Iteration   1: 16.123 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.123 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.569 ±(99.9%) 0.284 ms/op
Iteration   1: 8.394 ±(99.9%) 0.154 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.394 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 21.867 ±(99.9%) 0.347 ms/op
Iteration   1: 8.814 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.814 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 43.573 ±(99.9%) 1.423 ms/op
Iteration   1: 27.747 ±(99.9%) 0.136 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.747 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 22.755 ±(99.9%) 1.128 ms/op
Iteration   1: 13.475 ±(99.9%) 0.473 ms/op
                 createUser·p0.00:   3.953 ms/op
                 createUser·p0.50:   11.665 ms/op
                 createUser·p0.90:   23.331 ms/op
                 createUser·p0.95:   30.625 ms/op
                 createUser·p0.99:   40.420 ms/op
                 createUser·p0.999:  41.002 ms/op
                 createUser·p0.9999: 41.288 ms/op
                 createUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2355
  mean =     13.475 ±(99.9%) 0.473 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 759 
    [10.000, 15.000) = 1091 
    [15.000, 20.000) = 205 
    [20.000, 25.000) = 137 
    [25.000, 30.000) = 40 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      3.953 ms/op
     p(50.0000) =     11.665 ms/op
     p(90.0000) =     23.331 ms/op
     p(95.0000) =     30.625 ms/op
     p(99.0000) =     40.420 ms/op
     p(99.9000) =     41.002 ms/op
     p(99.9900) =     41.288 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.933 ±(99.9%) 0.419 ms/op
Iteration   1: 6.732 ±(99.9%) 0.145 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   6.373 ms/op
                 existUser·p0.90:   9.208 ms/op
                 existUser·p0.95:   12.329 ms/op
                 existUser·p0.99:   18.216 ms/op
                 existUser·p0.999:  23.962 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4729
  mean =      6.732 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 944 
    [ 5.000,  7.500) = 2609 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      6.373 ms/op
     p(90.0000) =      9.208 ms/op
     p(95.0000) =     12.329 ms/op
     p(99.0000) =     18.216 ms/op
     p(99.9000) =     23.962 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 21.915 ±(99.9%) 0.823 ms/op
Iteration   1: 11.275 ±(99.9%) 0.327 ms/op
                 getUser·p0.00:   4.293 ms/op
                 getUser·p0.50:   10.207 ms/op
                 getUser·p0.90:   14.336 ms/op
                 getUser·p0.95:   19.562 ms/op
                 getUser·p0.99:   47.448 ms/op
                 getUser·p0.999:  52.298 ms/op
                 getUser·p0.9999: 52.363 ms/op
                 getUser·p1.00:   52.363 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 2847
  mean =     11.275 ±(99.9%) 0.327 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5 
    [ 5.000, 10.000) = 1362 
    [10.000, 15.000) = 1234 
    [15.000, 20.000) = 111 
    [20.000, 25.000) = 96 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 20 
    [50.000, 55.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      4.293 ms/op
     p(50.0000) =     10.207 ms/op
     p(90.0000) =     14.336 ms/op
     p(95.0000) =     19.562 ms/op
     p(99.0000) =     47.448 ms/op
     p(99.9000) =     52.298 ms/op
     p(99.9900) =     52.363 ms/op
     p(99.9990) =     52.363 ms/op
     p(99.9999) =     52.363 ms/op
    p(100.0000) =     52.363 ms/op


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
# Warmup Iteration   1: 40.265 ±(99.9%) 2.130 ms/op
Iteration   1: 26.305 ±(99.9%) 0.717 ms/op
                 listUser·p0.00:   4.350 ms/op
                 listUser·p0.50:   24.478 ms/op
                 listUser·p0.90:   36.307 ms/op
                 listUser·p0.95:   38.142 ms/op
                 listUser·p0.99:   51.889 ms/op
                 listUser·p0.999:  63.983 ms/op
                 listUser·p0.9999: 64.291 ms/op
                 listUser·p1.00:   64.291 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1223
  mean =     26.305 ±(99.9%) 0.717 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 29 
    [15.000, 20.000) = 91 
    [20.000, 25.000) = 529 
    [25.000, 30.000) = 215 
    [30.000, 35.000) = 212 
    [35.000, 40.000) = 100 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 13 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.350 ms/op
     p(50.0000) =     24.478 ms/op
     p(90.0000) =     36.307 ms/op
     p(95.0000) =     38.142 ms/op
     p(99.0000) =     51.889 ms/op
     p(99.9000) =     63.983 ms/op
     p(99.9900) =     64.291 ms/op
     p(99.9990) =     64.291 ms/op
     p(99.9999) =     64.291 ms/op
    p(100.0000) =     64.291 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.112          ops/ms
Client.existUser                       thrpt         3.953          ops/ms
Client.getUser                         thrpt         2.480          ops/ms
Client.listUser                        thrpt         0.864          ops/ms
Client.createUser                       avgt        16.123           ms/op
Client.existUser                        avgt         8.394           ms/op
Client.getUser                          avgt         8.814           ms/op
Client.listUser                         avgt        27.747           ms/op
Client.createUser                     sample  2355  13.475 ± 0.473   ms/op
Client.createUser:createUser·p0.00    sample         3.953           ms/op
Client.createUser:createUser·p0.50    sample        11.665           ms/op
Client.createUser:createUser·p0.90    sample        23.331           ms/op
Client.createUser:createUser·p0.95    sample        30.625           ms/op
Client.createUser:createUser·p0.99    sample        40.420           ms/op
Client.createUser:createUser·p0.999   sample        41.002           ms/op
Client.createUser:createUser·p0.9999  sample        41.288           ms/op
Client.createUser:createUser·p1.00    sample        41.288           ms/op
Client.existUser                      sample  4729   6.732 ± 0.145   ms/op
Client.existUser:existUser·p0.00      sample         1.027           ms/op
Client.existUser:existUser·p0.50      sample         6.373           ms/op
Client.existUser:existUser·p0.90      sample         9.208           ms/op
Client.existUser:existUser·p0.95      sample        12.329           ms/op
Client.existUser:existUser·p0.99      sample        18.216           ms/op
Client.existUser:existUser·p0.999     sample        23.962           ms/op
Client.existUser:existUser·p0.9999    sample        24.281           ms/op
Client.existUser:existUser·p1.00      sample        24.281           ms/op
Client.getUser                        sample  2847  11.275 ± 0.327   ms/op
Client.getUser:getUser·p0.00          sample         4.293           ms/op
Client.getUser:getUser·p0.50          sample        10.207           ms/op
Client.getUser:getUser·p0.90          sample        14.336           ms/op
Client.getUser:getUser·p0.95          sample        19.562           ms/op
Client.getUser:getUser·p0.99          sample        47.448           ms/op
Client.getUser:getUser·p0.999         sample        52.298           ms/op
Client.getUser:getUser·p0.9999        sample        52.363           ms/op
Client.getUser:getUser·p1.00          sample        52.363           ms/op
Client.listUser                       sample  1223  26.305 ± 0.717   ms/op
Client.listUser:listUser·p0.00        sample         4.350           ms/op
Client.listUser:listUser·p0.50        sample        24.478           ms/op
Client.listUser:listUser·p0.90        sample        36.307           ms/op
Client.listUser:listUser·p0.95        sample        38.142           ms/op
Client.listUser:listUser·p0.99        sample        51.889           ms/op
Client.listUser:listUser·p0.999       sample        63.983           ms/op
Client.listUser:listUser·p0.9999      sample        64.291           ms/op
Client.listUser:listUser·p1.00        sample        64.291           ms/op
