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
# Warmup Iteration   1: 1.438 ops/ms
Iteration   1: 7.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.174 ops/ms


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
# Warmup Iteration   1: 5.763 ops/ms
Iteration   1: 12.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.484 ops/ms


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
# Warmup Iteration   1: 5.602 ops/ms
Iteration   1: 14.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.159 ops/ms


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
# Warmup Iteration   1: 4.516 ops/ms
Iteration   1: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.140 ops/ms


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.077 ms/op
Iteration   1: 1.983 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.983 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.052 ms/op
Iteration   1: 1.848 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.074 ms/op
Iteration   1: 2.166 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.166 ms/op


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.099 ms/op
Iteration   1: 3.492 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.492 ms/op


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
# Warmup Iteration   1: 3.438 ±(99.9%) 0.087 ms/op
Iteration   1: 2.348 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.884 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  16.400 ms/op
                 createUser·p0.9999: 18.577 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13959
  mean =      2.348 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 10647 
    [ 2.500,  3.750) = 2300 
    [ 3.750,  5.000) = 728 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     18.577 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.077 ms/op
Iteration   1: 1.864 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.058 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   2.714 ms/op
                 existUser·p0.999:  18.375 ms/op
                 existUser·p0.9999: 23.890 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17232
  mean =      1.864 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16881 
    [ 2.500,  5.000) = 287 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.058 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      2.714 ms/op
     p(99.9000) =     18.375 ms/op
     p(99.9900) =     23.890 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.077 ms/op
Iteration   1: 1.950 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   1.886 ms/op
                 getUser·p0.90:   2.367 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.132 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 12.809 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16359
  mean =      1.950 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 259 
    [ 1.250,  2.500) = 14985 
    [ 2.500,  3.750) = 1018 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.132 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     12.809 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.205 ms/op
Iteration   1: 3.780 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.853 ms/op
                 listUser·p0.99:   8.032 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8450
  mean =      3.780 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 250 
    [ 2.500,  3.750) = 4489 
    [ 3.750,  5.000) = 3317 
    [ 5.000,  6.250) = 219 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.853 ms/op
     p(99.0000) =      8.032 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.174          ops/ms
ClientSimple.existUser                       thrpt         12.484          ops/ms
ClientSimple.getUser                         thrpt         14.159          ops/ms
ClientSimple.listUser                        thrpt          9.140          ops/ms
ClientSimple.createUser                       avgt          1.983           ms/op
ClientSimple.existUser                        avgt          1.848           ms/op
ClientSimple.getUser                          avgt          2.166           ms/op
ClientSimple.listUser                         avgt          3.492           ms/op
ClientSimple.createUser                     sample  13959   2.348 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.624           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.030           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.087           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.400           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.577           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.005           ms/op
ClientSimple.existUser                      sample  17232   1.864 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.887           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.714           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.375           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.890           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.838           ms/op
ClientSimple.getUser                        sample  16359   1.950 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.624           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.886           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.132           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.222           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.809           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.976           ms/op
ClientSimple.listUser                       sample   8450   3.780 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.670           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.853           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.032           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.024           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.399           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.399           ms/op

Benchmark result is saved to 1711067786566.json
