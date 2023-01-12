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
# Warmup Iteration   1: 1.074 ops/ms
Iteration   1: 2.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.643 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.672 ops/ms
Iteration   1: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.491 ops/ms


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
# Warmup Iteration   1: 2.164 ops/ms
Iteration   1: 4.434 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.434 ops/ms


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
# Warmup Iteration   1: 0.861 ops/ms
Iteration   1: 1.358 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.358 ops/ms


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
# Warmup Iteration   1: 16.271 ±(99.9%) 0.333 ms/op
Iteration   1: 7.515 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.515 ms/op


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
# Warmup Iteration   1: 6.578 ±(99.9%) 0.071 ms/op
Iteration   1: 4.142 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.142 ms/op


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
# Warmup Iteration   1: 10.066 ±(99.9%) 0.175 ms/op
Iteration   1: 4.830 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.830 ms/op


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
# Warmup Iteration   1: 27.822 ±(99.9%) 0.690 ms/op
Iteration   1: 18.811 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.811 ms/op


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
# Warmup Iteration   1: 12.688 ±(99.9%) 0.394 ms/op
Iteration   1: 7.859 ±(99.9%) 0.118 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   7.684 ms/op
                 createUser·p0.90:   8.552 ms/op
                 createUser·p0.95:   10.130 ms/op
                 createUser·p0.99:   17.629 ms/op
                 createUser·p0.999:  23.621 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4078
  mean =      7.859 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 127 
    [ 5.000,  7.500) = 1452 
    [ 7.500, 10.000) = 2293 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =      8.552 ms/op
     p(95.0000) =     10.130 ms/op
     p(99.0000) =     17.629 ms/op
     p(99.9000) =     23.621 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 6.861 ±(99.9%) 0.224 ms/op
Iteration   1: 4.779 ±(99.9%) 0.079 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   7.979 ms/op
                 existUser·p0.99:   13.091 ms/op
                 existUser·p0.999:  18.698 ms/op
                 existUser·p0.9999: 19.268 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6696
  mean =      4.779 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 295 
    [ 2.500,  3.750) = 1890 
    [ 3.750,  5.000) = 2310 
    [ 5.000,  6.250) = 1715 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     13.091 ms/op
     p(99.9000) =     18.698 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 11.087 ±(99.9%) 0.367 ms/op
Iteration   1: 4.884 ±(99.9%) 0.071 ms/op
                 getUser·p0.00:   2.021 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  23.226 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6545
  mean =      4.884 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 5090 
    [ 5.000,  7.500) = 1295 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     23.226 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 27.443 ±(99.9%) 1.040 ms/op
Iteration   1: 17.063 ±(99.9%) 0.252 ms/op
                 listUser·p0.00:   6.259 ms/op
                 listUser·p0.50:   17.170 ms/op
                 listUser·p0.90:   19.137 ms/op
                 listUser·p0.95:   19.887 ms/op
                 listUser·p0.99:   34.910 ms/op
                 listUser·p0.999:  41.574 ms/op
                 listUser·p0.9999: 42.533 ms/op
                 listUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1860
  mean =     17.063 ±(99.9%) 0.252 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 18 
    [10.000, 15.000) = 491 
    [15.000, 20.000) = 1261 
    [20.000, 25.000) = 53 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      6.259 ms/op
     p(50.0000) =     17.170 ms/op
     p(90.0000) =     19.137 ms/op
     p(95.0000) =     19.887 ms/op
     p(99.0000) =     34.910 ms/op
     p(99.9000) =     41.574 ms/op
     p(99.9900) =     42.533 ms/op
     p(99.9990) =     42.533 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.643          ops/ms
Client.existUser                       thrpt         6.491          ops/ms
Client.getUser                         thrpt         4.434          ops/ms
Client.listUser                        thrpt         1.358          ops/ms
Client.createUser                       avgt         7.515           ms/op
Client.existUser                        avgt         4.142           ms/op
Client.getUser                          avgt         4.830           ms/op
Client.listUser                         avgt        18.811           ms/op
Client.createUser                     sample  4078   7.859 ± 0.118   ms/op
Client.createUser:createUser·p0.00    sample         1.237           ms/op
Client.createUser:createUser·p0.50    sample         7.684           ms/op
Client.createUser:createUser·p0.90    sample         8.552           ms/op
Client.createUser:createUser·p0.95    sample        10.130           ms/op
Client.createUser:createUser·p0.99    sample        17.629           ms/op
Client.createUser:createUser·p0.999   sample        23.621           ms/op
Client.createUser:createUser·p0.9999  sample        23.822           ms/op
Client.createUser:createUser·p1.00    sample        23.822           ms/op
Client.existUser                      sample  6696   4.779 ± 0.079   ms/op
Client.existUser:existUser·p0.00      sample         0.969           ms/op
Client.existUser:existUser·p0.50      sample         4.719           ms/op
Client.existUser:existUser·p0.90      sample         5.816           ms/op
Client.existUser:existUser·p0.95      sample         7.979           ms/op
Client.existUser:existUser·p0.99      sample        13.091           ms/op
Client.existUser:existUser·p0.999     sample        18.698           ms/op
Client.existUser:existUser·p0.9999    sample        19.268           ms/op
Client.existUser:existUser·p1.00      sample        19.268           ms/op
Client.getUser                        sample  6545   4.884 ± 0.071   ms/op
Client.getUser:getUser·p0.00          sample         2.021           ms/op
Client.getUser:getUser·p0.50          sample         4.637           ms/op
Client.getUser:getUser·p0.90          sample         5.399           ms/op
Client.getUser:getUser·p0.95          sample         6.160           ms/op
Client.getUser:getUser·p0.99          sample        10.895           ms/op
Client.getUser:getUser·p0.999         sample        23.226           ms/op
Client.getUser:getUser·p0.9999        sample        25.461           ms/op
Client.getUser:getUser·p1.00          sample        25.461           ms/op
Client.listUser                       sample  1860  17.063 ± 0.252   ms/op
Client.listUser:listUser·p0.00        sample         6.259           ms/op
Client.listUser:listUser·p0.50        sample        17.170           ms/op
Client.listUser:listUser·p0.90        sample        19.137           ms/op
Client.listUser:listUser·p0.95        sample        19.887           ms/op
Client.listUser:listUser·p0.99        sample        34.910           ms/op
Client.listUser:listUser·p0.999       sample        41.574           ms/op
Client.listUser:listUser·p0.9999      sample        42.533           ms/op
Client.listUser:listUser·p1.00        sample        42.533           ms/op
