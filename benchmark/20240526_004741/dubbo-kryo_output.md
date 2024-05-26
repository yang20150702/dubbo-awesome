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
# Warmup Iteration   1: 1.581 ops/ms
Iteration   1: 7.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.306 ops/ms


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
# Warmup Iteration   1: 6.479 ops/ms
Iteration   1: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.949 ops/ms


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
# Warmup Iteration   1: 6.388 ops/ms
Iteration   1: 14.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.436 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.547 ops/ms
Iteration   1: 9.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.656 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.072 ms/op
Iteration   1: 2.321 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.321 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.062 ms/op
Iteration   1: 2.009 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.009 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.053 ms/op
Iteration   1: 2.314 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.314 ms/op


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
# Warmup Iteration   1: 5.387 ±(99.9%) 0.128 ms/op
Iteration   1: 3.524 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.524 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.101 ms/op
Iteration   1: 2.567 ±(99.9%) 0.071 ms/op
                 createUser·p0.00:   0.316 ms/op
                 createUser·p0.50:   2.286 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   10.692 ms/op
                 createUser·p0.999:  42.729 ms/op
                 createUser·p0.9999: 52.980 ms/op
                 createUser·p1.00:   55.443 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12440
  mean =      2.567 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12201 
    [ 5.000, 10.000) = 105 
    [10.000, 15.000) = 68 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 20 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =     10.692 ms/op
     p(99.9000) =     42.729 ms/op
     p(99.9900) =     52.980 ms/op
     p(99.9990) =     55.443 ms/op
     p(99.9999) =     55.443 ms/op
    p(100.0000) =     55.443 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.083 ms/op
Iteration   1: 2.129 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   1.993 ms/op
                 existUser·p0.90:   2.572 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   3.762 ms/op
                 existUser·p0.999:  25.788 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15011
  mean =      2.129 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13109 
    [ 2.500,  5.000) = 1811 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.762 ms/op
     p(99.9000) =     25.788 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.202 ms/op
Iteration   1: 2.152 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.087 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 11.978 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14854
  mean =      2.152 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 237 
    [ 1.250,  2.500) = 12043 
    [ 2.500,  3.750) = 2401 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.087 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     11.978 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.119 ms/op
Iteration   1: 3.545 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.962 ms/op
                 listUser·p0.999:  25.395 ms/op
                 listUser·p0.9999: 25.559 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9018
  mean =      3.545 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 501 
    [ 2.500,  5.000) = 8291 
    [ 5.000,  7.500) = 193 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.962 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.306          ops/ms
ClientSimple.existUser                       thrpt         12.949          ops/ms
ClientSimple.getUser                         thrpt         14.436          ops/ms
ClientSimple.listUser                        thrpt          9.656          ops/ms
ClientSimple.createUser                       avgt          2.321           ms/op
ClientSimple.existUser                        avgt          2.009           ms/op
ClientSimple.getUser                          avgt          2.314           ms/op
ClientSimple.listUser                         avgt          3.524           ms/op
ClientSimple.createUser                     sample  12440   2.567 ± 0.071   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.316           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.281           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.692           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.729           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         52.980           ms/op
ClientSimple.createUser:createUser·p1.00    sample         55.443           ms/op
ClientSimple.existUser                      sample  15011   2.129 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.529           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.993           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.762           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.788           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.640           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.640           ms/op
ClientSimple.getUser                        sample  14854   2.152 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.613           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.087           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.826           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.781           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.978           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample   9018   3.545 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.850           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.962           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.395           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.559           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.559           ms/op

Benchmark result is saved to 1716684177245.json
