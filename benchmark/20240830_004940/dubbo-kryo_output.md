# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.035 ops/ms
Iteration   1: 7.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.185 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.143 ops/ms
Iteration   1: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.097 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.225 ops/ms
Iteration   1: 13.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.775 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ops/ms
Iteration   1: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.573 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ±(99.9%) 0.061 ms/op
Iteration   1: 2.101 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ±(99.9%) 0.044 ms/op
Iteration   1: 1.931 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.931 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.060 ms/op
Iteration   1: 2.071 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ±(99.9%) 0.089 ms/op
Iteration   1: 3.503 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.503 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ±(99.9%) 0.080 ms/op
Iteration   1: 2.143 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   1.786 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14890
  mean =      2.143 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12450 
    [ 2.500,  5.000) = 2291 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ±(99.9%) 0.077 ms/op
Iteration   1: 1.909 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  11.555 ms/op
                 existUser·p0.9999: 11.812 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16746
  mean =      1.909 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 537 
    [ 1.250,  2.500) = 15724 
    [ 2.500,  3.750) = 280 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     11.555 ms/op
     p(99.9900) =     11.812 ms/op
     p(99.9990) =     11.846 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ±(99.9%) 0.076 ms/op
Iteration   1: 2.241 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   4.995 ms/op
                 getUser·p0.999:  17.847 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14340
  mean =      2.241 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 10442 
    [ 2.500,  3.750) = 3471 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.995 ms/op
     p(99.9000) =     17.847 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ±(99.9%) 0.125 ms/op
Iteration   1: 3.591 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.807 ms/op
                 listUser·p0.999:  7.791 ms/op
                 listUser·p0.9999: 7.881 ms/op
                 listUser·p1.00:   7.881 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8911
  mean =      3.591 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 39 
    [2.000, 2.500) = 337 
    [2.500, 3.000) = 939 
    [3.000, 3.500) = 2704 
    [3.500, 4.000) = 2973 
    [4.000, 4.500) = 1491 
    [4.500, 5.000) = 230 
    [5.000, 5.500) = 65 
    [5.500, 6.000) = 60 
    [6.000, 6.500) = 31 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.807 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =      7.881 ms/op
     p(99.9990) =      7.881 ms/op
     p(99.9999) =      7.881 ms/op
    p(100.0000) =      7.881 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.185          ops/ms
ClientSimple.existUser                       thrpt         13.097          ops/ms
ClientSimple.getUser                         thrpt         13.775          ops/ms
ClientSimple.listUser                        thrpt          8.573          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.931           ms/op
ClientSimple.getUser                          avgt          2.071           ms/op
ClientSimple.listUser                         avgt          3.503           ms/op
ClientSimple.createUser                     sample  14890   2.143 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.853           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.786           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.346           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.022           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.104           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.988           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.087           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.087           ms/op
ClientSimple.existUser                      sample  16746   1.909 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.621           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.555           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.812           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.846           ms/op
ClientSimple.getUser                        sample  14340   2.241 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.654           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.995           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.847           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.416           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.416           ms/op
ClientSimple.listUser                       sample   8911   3.591 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.507           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.807           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.791           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.881           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.881           ms/op

Benchmark result is saved to 1724978711060.json
