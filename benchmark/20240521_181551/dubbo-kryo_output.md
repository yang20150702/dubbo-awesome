# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.590 ops/ms
Iteration   1: 6.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.399 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ops/ms
Iteration   1: 11.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.678 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.130 ops/ms
Iteration   1: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.701 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ops/ms
Iteration   1: 8.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.825 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ±(99.9%) 0.088 ms/op
Iteration   1: 2.315 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ±(99.9%) 0.050 ms/op
Iteration   1: 2.027 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.027 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ±(99.9%) 0.057 ms/op
Iteration   1: 2.106 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ±(99.9%) 0.107 ms/op
Iteration   1: 3.638 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.112 ms/op
Iteration   1: 1.954 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   1.745 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  19.060 ms/op
                 createUser·p0.9999: 21.349 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16343
  mean =      1.954 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14627 
    [ 2.500,  5.000) = 1409 
    [ 5.000,  7.500) = 147 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     19.060 ms/op
     p(99.9900) =     21.349 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.993 ±(99.9%) 0.065 ms/op
Iteration   1: 1.735 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.093 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   4.515 ms/op
                 existUser·p0.999:  20.590 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18630
  mean =      1.735 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18040 
    [ 2.500,  5.000) = 476 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.093 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      4.515 ms/op
     p(99.9000) =     20.590 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.211 ±(99.9%) 0.091 ms/op
Iteration   1: 2.145 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.491 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  12.128 ms/op
                 getUser·p0.9999: 16.459 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14893
  mean =      2.145 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 531 
    [ 1.250,  2.500) = 11334 
    [ 2.500,  3.750) = 2826 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     12.128 ms/op
     p(99.9900) =     16.459 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.872 ±(99.9%) 0.181 ms/op
Iteration   1: 3.884 ±(99.9%) 0.092 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  43.469 ms/op
                 listUser·p0.9999: 50.987 ms/op
                 listUser·p1.00:   50.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8237
  mean =      3.884 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7830 
    [ 5.000, 10.000) = 310 
    [10.000, 15.000) = 45 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     43.469 ms/op
     p(99.9900) =     50.987 ms/op
     p(99.9990) =     50.987 ms/op
     p(99.9999) =     50.987 ms/op
    p(100.0000) =     50.987 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.399          ops/ms
ClientSimple.existUser                       thrpt         11.678          ops/ms
ClientSimple.getUser                         thrpt         12.701          ops/ms
ClientSimple.listUser                        thrpt          8.825          ops/ms
ClientSimple.createUser                       avgt          2.315           ms/op
ClientSimple.existUser                        avgt          2.027           ms/op
ClientSimple.getUser                          avgt          2.106           ms/op
ClientSimple.listUser                         avgt          3.638           ms/op
ClientSimple.createUser                     sample  16343   1.954 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.745           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.447           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.060           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.822           ms/op
ClientSimple.existUser                      sample  18630   1.735 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.472           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.093           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.515           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.590           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.823           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.823           ms/op
ClientSimple.getUser                        sample  14893   2.145 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.491           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.965           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.128           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.459           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.515           ms/op
ClientSimple.listUser                       sample   8237   3.884 ± 0.092   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.936           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.670           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.665           ms/op
ClientSimple.listUser:listUser·p0.999       sample         43.469           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         50.987           ms/op
ClientSimple.listUser:listUser·p1.00        sample         50.987           ms/op

Benchmark result is saved to 1716315096640.json
