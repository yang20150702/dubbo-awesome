# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 7.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.228 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.607 ops/ms
Iteration   1: 13.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.297 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.786 ops/ms
Iteration   1: 13.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.164 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.781 ops/ms
Iteration   1: 8.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.734 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.072 ms/op
Iteration   1: 2.138 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ±(99.9%) 0.052 ms/op
Iteration   1: 1.944 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.944 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ±(99.9%) 0.062 ms/op
Iteration   1: 2.075 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.075 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.120 ms/op
Iteration   1: 3.153 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ±(99.9%) 0.093 ms/op
Iteration   1: 2.093 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.455 ms/op
                 createUser·p0.50:   1.960 ms/op
                 createUser·p0.90:   2.545 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   5.098 ms/op
                 createUser·p0.999:  23.523 ms/op
                 createUser·p0.9999: 25.622 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15135
  mean =      2.093 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13392 
    [ 2.500,  5.000) = 1587 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.545 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      5.098 ms/op
     p(99.9000) =     23.523 ms/op
     p(99.9900) =     25.622 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ±(99.9%) 0.074 ms/op
Iteration   1: 1.954 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   3.174 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 12.525 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16408
  mean =      1.954 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 471 
    [ 1.250,  2.500) = 14297 
    [ 2.500,  3.750) = 1593 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.174 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     12.525 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.077 ±(99.9%) 0.081 ms/op
Iteration   1: 1.930 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.427 ms/op
                 getUser·p0.50:   1.774 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.708 ms/op
                 getUser·p0.99:   6.425 ms/op
                 getUser·p0.999:  13.076 ms/op
                 getUser·p0.9999: 16.527 ms/op
                 getUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16634
  mean =      1.930 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 941 
    [ 1.250,  2.500) = 14404 
    [ 2.500,  3.750) = 918 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.708 ms/op
     p(99.0000) =      6.425 ms/op
     p(99.9000) =     13.076 ms/op
     p(99.9900) =     16.527 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.149 ms/op
Iteration   1: 3.346 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9580
  mean =      3.346 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1676 
    [ 2.500,  3.750) = 4988 
    [ 3.750,  5.000) = 2692 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.228          ops/ms
ClientSimple.existUser                       thrpt         13.297          ops/ms
ClientSimple.getUser                         thrpt         13.164          ops/ms
ClientSimple.listUser                        thrpt          8.734          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.944           ms/op
ClientSimple.getUser                          avgt          2.075           ms/op
ClientSimple.listUser                         avgt          3.153           ms/op
ClientSimple.createUser                     sample  15135   2.093 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.455           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.960           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.545           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.098           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.523           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.622           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.968           ms/op
ClientSimple.existUser                      sample  16408   1.954 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.657           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.174           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.321           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.525           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.567           ms/op
ClientSimple.getUser                        sample  16634   1.930 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.427           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.774           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.708           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.425           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.076           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.527           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.712           ms/op
ClientSimple.listUser                       sample   9580   3.346 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.953           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.301           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.825           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.923           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.923           ms/op

Benchmark result is saved to 1713054846247.json
