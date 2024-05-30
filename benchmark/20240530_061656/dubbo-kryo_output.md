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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 6.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.508 ops/ms


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
# Warmup Iteration   1: 6.105 ops/ms
Iteration   1: 12.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.635 ops/ms


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
# Warmup Iteration   1: 5.087 ops/ms
Iteration   1: 12.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.608 ops/ms


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
# Warmup Iteration   1: 3.994 ops/ms
Iteration   1: 7.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.312 ops/ms


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.075 ms/op
Iteration   1: 2.243 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.243 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.079 ms/op
Iteration   1: 2.160 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.160 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.065 ms/op
Iteration   1: 2.238 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.238 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.123 ms/op
Iteration   1: 3.465 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.465 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.087 ms/op
Iteration   1: 2.344 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   6.667 ms/op
                 createUser·p0.999:  47.467 ms/op
                 createUser·p0.9999: 49.079 ms/op
                 createUser·p1.00:   49.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13712
  mean =      2.344 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13464 
    [ 5.000, 10.000) = 180 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      6.667 ms/op
     p(99.9000) =     47.467 ms/op
     p(99.9900) =     49.079 ms/op
     p(99.9990) =     49.152 ms/op
     p(99.9999) =     49.152 ms/op
    p(100.0000) =     49.152 ms/op


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
# Warmup Iteration   1: 3.087 ±(99.9%) 0.075 ms/op
Iteration   1: 1.875 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.087 ms/op
                 existUser·p0.95:   2.511 ms/op
                 existUser·p0.99:   3.803 ms/op
                 existUser·p0.999:  26.834 ms/op
                 existUser·p0.9999: 28.069 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17049
  mean =      1.875 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16176 
    [ 2.500,  5.000) = 749 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.087 ms/op
     p(95.0000) =      2.511 ms/op
     p(99.0000) =      3.803 ms/op
     p(99.9000) =     26.834 ms/op
     p(99.9900) =     28.069 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.104 ms/op
Iteration   1: 2.257 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.916 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  13.218 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14123
  mean =      2.257 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 10079 
    [ 2.500,  3.750) = 3733 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =     13.218 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.166 ms/op
Iteration   1: 3.307 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   0.673 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.335 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  26.257 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9696
  mean =      3.307 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 989 
    [ 2.500,  5.000) = 8551 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.335 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     26.257 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.508          ops/ms
ClientSimple.existUser                       thrpt         12.635          ops/ms
ClientSimple.getUser                         thrpt         12.608          ops/ms
ClientSimple.listUser                        thrpt          7.312          ops/ms
ClientSimple.createUser                       avgt          2.243           ms/op
ClientSimple.existUser                        avgt          2.160           ms/op
ClientSimple.getUser                          avgt          2.238           ms/op
ClientSimple.listUser                         avgt          3.465           ms/op
ClientSimple.createUser                     sample  13712   2.344 ± 0.067   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.820           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.133           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.667           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.467           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         49.079           ms/op
ClientSimple.createUser:createUser·p1.00    sample         49.152           ms/op
ClientSimple.existUser                      sample  17049   1.875 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.087           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.803           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.834           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.069           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.115           ms/op
ClientSimple.getUser                        sample  14123   2.257 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.524           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.071           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.218           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.599           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.713           ms/op
ClientSimple.listUser                       sample   9696   3.307 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.673           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.994           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.335           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.669           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.257           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.132           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.132           ms/op

Benchmark result is saved to 1717049568355.json
