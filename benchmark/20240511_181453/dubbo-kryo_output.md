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
# Warmup Iteration   1: 1.661 ops/ms
Iteration   1: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.816 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.101 ops/ms
Iteration   1: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.695 ops/ms


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
# Warmup Iteration   1: 4.574 ops/ms
Iteration   1: 11.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.162 ops/ms


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
# Warmup Iteration   1: 4.513 ops/ms
Iteration   1: 7.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.596 ops/ms


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.073 ms/op
Iteration   1: 2.128 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.128 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.052 ms/op
Iteration   1: 1.892 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.064 ms/op
Iteration   1: 2.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.097 ms/op


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
# Warmup Iteration   1: 4.798 ±(99.9%) 0.119 ms/op
Iteration   1: 3.439 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.439 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.117 ms/op
Iteration   1: 2.349 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.079 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.997 ms/op
                 createUser·p0.99:   9.394 ms/op
                 createUser·p0.999:  29.229 ms/op
                 createUser·p0.9999: 31.073 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13663
  mean =      2.349 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11426 
    [ 2.500,  5.000) = 1840 
    [ 5.000,  7.500) = 236 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.997 ms/op
     p(99.0000) =      9.394 ms/op
     p(99.9000) =     29.229 ms/op
     p(99.9900) =     31.073 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.068 ms/op
Iteration   1: 2.103 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.007 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.576 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 20.692 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15220
  mean =      2.103 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13908 
    [ 2.500,  5.000) = 1192 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.576 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     20.692 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.101 ms/op
Iteration   1: 2.269 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  27.156 ms/op
                 getUser·p0.9999: 44.688 ms/op
                 getUser·p1.00:   45.023 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14257
  mean =      2.269 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14108 
    [ 5.000, 10.000) = 85 
    [10.000, 15.000) = 9 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 19 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =     27.156 ms/op
     p(99.9900) =     44.688 ms/op
     p(99.9990) =     45.023 ms/op
     p(99.9999) =     45.023 ms/op
    p(100.0000) =     45.023 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.134 ms/op
Iteration   1: 3.470 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   8.384 ms/op
                 listUser·p0.999:  20.702 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9214
  mean =      3.470 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 732 
    [ 2.500,  5.000) = 8163 
    [ 5.000,  7.500) = 213 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.384 ms/op
     p(99.9000) =     20.702 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.816          ops/ms
ClientSimple.existUser                       thrpt         12.695          ops/ms
ClientSimple.getUser                         thrpt         11.162          ops/ms
ClientSimple.listUser                        thrpt          7.596          ops/ms
ClientSimple.createUser                       avgt          2.128           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          2.097           ms/op
ClientSimple.listUser                         avgt          3.439           ms/op
ClientSimple.createUser                     sample  13663   2.349 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.842           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.079           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.997           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.394           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.229           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.073           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.097           ms/op
ClientSimple.existUser                      sample  15220   2.103 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.628           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.576           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.578           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.692           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.709           ms/op
ClientSimple.getUser                        sample  14257   2.269 ± 0.046   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.022           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.156           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         44.688           ms/op
ClientSimple.getUser:getUser·p1.00          sample         45.023           ms/op
ClientSimple.listUser                       sample   9214   3.470 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.957           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.384           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.702           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.808           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.808           ms/op

Benchmark result is saved to 1715451050772.json
