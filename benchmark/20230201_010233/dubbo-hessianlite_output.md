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
# Warmup Iteration   1: 1.132 ops/ms
Iteration   1: 2.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.235 ops/ms


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
# Warmup Iteration   1: 2.489 ops/ms
Iteration   1: 6.197 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.197 ops/ms


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
# Warmup Iteration   1: 1.797 ops/ms
Iteration   1: 4.688 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.688 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.953 ops/ms
Iteration   1: 1.760 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.760 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 17.153 ±(99.9%) 0.316 ms/op
Iteration   1: 7.218 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.218 ms/op


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
# Warmup Iteration   1: 6.582 ±(99.9%) 0.082 ms/op
Iteration   1: 3.849 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.849 ms/op


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
# Warmup Iteration   1: 11.529 ±(99.9%) 0.227 ms/op
Iteration   1: 4.475 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.475 ms/op


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
# Warmup Iteration   1: 23.733 ±(99.9%) 0.474 ms/op
Iteration   1: 15.726 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.726 ms/op


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
# Warmup Iteration   1: 11.470 ±(99.9%) 0.384 ms/op
Iteration   1: 6.156 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   5.792 ms/op
                 createUser·p0.90:   7.864 ms/op
                 createUser·p0.95:   8.498 ms/op
                 createUser·p0.99:   22.610 ms/op
                 createUser·p0.999:  27.931 ms/op
                 createUser·p0.9999: 29.524 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5206
  mean =      6.156 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 766 
    [ 5.000,  7.500) = 3245 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      8.498 ms/op
     p(99.0000) =     22.610 ms/op
     p(99.9000) =     27.931 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 6.403 ±(99.9%) 0.186 ms/op
Iteration   1: 2.581 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   0.276 ms/op
                 existUser·p0.50:   2.318 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  24.301 ms/op
                 existUser·p0.9999: 30.435 ms/op
                 existUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12391
  mean =      2.581 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8493 
    [ 2.500,  5.000) = 3453 
    [ 5.000,  7.500) = 231 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.276 ms/op
     p(50.0000) =      2.318 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     24.301 ms/op
     p(99.9900) =     30.435 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 10.520 ±(99.9%) 0.408 ms/op
Iteration   1: 4.683 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.858 ms/op
                 getUser·p0.99:   14.042 ms/op
                 getUser·p0.999:  27.903 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6818
  mean =      4.683 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 5924 
    [ 5.000,  7.500) = 763 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.858 ms/op
     p(99.0000) =     14.042 ms/op
     p(99.9000) =     27.903 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 25.942 ±(99.9%) 0.687 ms/op
Iteration   1: 14.554 ±(99.9%) 0.195 ms/op
                 listUser·p0.00:   5.751 ms/op
                 listUser·p0.50:   13.795 ms/op
                 listUser·p0.90:   17.924 ms/op
                 listUser·p0.95:   19.694 ms/op
                 listUser·p0.99:   23.858 ms/op
                 listUser·p0.999:  32.125 ms/op
                 listUser·p0.9999: 33.063 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2189
  mean =     14.554 ±(99.9%) 0.195 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 1416 
    [15.000, 17.500) = 294 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.751 ms/op
     p(50.0000) =     13.795 ms/op
     p(90.0000) =     17.924 ms/op
     p(95.0000) =     19.694 ms/op
     p(99.0000) =     23.858 ms/op
     p(99.9000) =     32.125 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     33.063 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.235          ops/ms
Client.existUser                       thrpt          6.197          ops/ms
Client.getUser                         thrpt          4.688          ops/ms
Client.listUser                        thrpt          1.760          ops/ms
Client.createUser                       avgt          7.218           ms/op
Client.existUser                        avgt          3.849           ms/op
Client.getUser                          avgt          4.475           ms/op
Client.listUser                         avgt         15.726           ms/op
Client.createUser                     sample   5206   6.156 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample          1.733           ms/op
Client.createUser:createUser·p0.50    sample          5.792           ms/op
Client.createUser:createUser·p0.90    sample          7.864           ms/op
Client.createUser:createUser·p0.95    sample          8.498           ms/op
Client.createUser:createUser·p0.99    sample         22.610           ms/op
Client.createUser:createUser·p0.999   sample         27.931           ms/op
Client.createUser:createUser·p0.9999  sample         29.524           ms/op
Client.createUser:createUser·p1.00    sample         29.524           ms/op
Client.existUser                      sample  12391   2.581 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample          0.276           ms/op
Client.existUser:existUser·p0.50      sample          2.318           ms/op
Client.existUser:existUser·p0.90      sample          2.879           ms/op
Client.existUser:existUser·p0.95      sample          3.580           ms/op
Client.existUser:existUser·p0.99      sample          9.798           ms/op
Client.existUser:existUser·p0.999     sample         24.301           ms/op
Client.existUser:existUser·p0.9999    sample         30.435           ms/op
Client.existUser:existUser·p1.00      sample         32.113           ms/op
Client.getUser                        sample   6818   4.683 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample          1.227           ms/op
Client.getUser:getUser·p0.50          sample          4.399           ms/op
Client.getUser:getUser·p0.90          sample          5.284           ms/op
Client.getUser:getUser·p0.95          sample          5.858           ms/op
Client.getUser:getUser·p0.99          sample         14.042           ms/op
Client.getUser:getUser·p0.999         sample         27.903           ms/op
Client.getUser:getUser·p0.9999        sample         28.705           ms/op
Client.getUser:getUser·p1.00          sample         28.705           ms/op
Client.listUser                       sample   2189  14.554 ± 0.195   ms/op
Client.listUser:listUser·p0.00        sample          5.751           ms/op
Client.listUser:listUser·p0.50        sample         13.795           ms/op
Client.listUser:listUser·p0.90        sample         17.924           ms/op
Client.listUser:listUser·p0.95        sample         19.694           ms/op
Client.listUser:listUser·p0.99        sample         23.858           ms/op
Client.listUser:listUser·p0.999       sample         32.125           ms/op
Client.listUser:listUser·p0.9999      sample         33.063           ms/op
Client.listUser:listUser·p1.00        sample         33.063           ms/op
