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
# Warmup Iteration   1: 1.752 ops/ms
Iteration   1: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.879 ops/ms


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
# Warmup Iteration   1: 6.004 ops/ms
Iteration   1: 12.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.087 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.760 ops/ms
Iteration   1: 14.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.136 ops/ms


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
# Warmup Iteration   1: 3.997 ops/ms
Iteration   1: 7.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.399 ops/ms


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.062 ms/op
Iteration   1: 2.447 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.447 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.058 ms/op
Iteration   1: 1.768 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.768 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.061 ms/op
Iteration   1: 1.913 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.913 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.104 ms/op
Iteration   1: 3.546 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.546 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.098 ms/op
Iteration   1: 2.346 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   11.056 ms/op
                 createUser·p0.999:  23.137 ms/op
                 createUser·p0.9999: 28.092 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13908
  mean =      2.346 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11014 
    [ 2.500,  5.000) = 2609 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =     11.056 ms/op
     p(99.9000) =     23.137 ms/op
     p(99.9900) =     28.092 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.109 ms/op
Iteration   1: 1.948 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   1.837 ms/op
                 existUser·p0.90:   2.492 ms/op
                 existUser·p0.95:   2.692 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 11.704 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16414
  mean =      1.948 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 14642 
    [ 2.500,  3.750) = 1507 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.492 ms/op
     p(95.0000) =      2.692 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     11.704 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.095 ms/op
Iteration   1: 2.043 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  26.381 ms/op
                 getUser·p0.9999: 27.178 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15970
  mean =      2.043 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13976 
    [ 2.500,  5.000) = 1890 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =     26.381 ms/op
     p(99.9900) =     27.178 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.152 ms/op
Iteration   1: 3.492 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.473 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.654 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.350 ms/op
                 listUser·p0.9999: 14.615 ms/op
                 listUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9156
  mean =      3.492 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1050 
    [ 2.500,  3.750) = 4698 
    [ 3.750,  5.000) = 3030 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.654 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.350 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.879          ops/ms
ClientSimple.existUser                       thrpt         12.087          ops/ms
ClientSimple.getUser                         thrpt         14.136          ops/ms
ClientSimple.listUser                        thrpt          7.399          ops/ms
ClientSimple.createUser                       avgt          2.447           ms/op
ClientSimple.existUser                        avgt          1.768           ms/op
ClientSimple.getUser                          avgt          1.913           ms/op
ClientSimple.listUser                         avgt          3.546           ms/op
ClientSimple.createUser                     sample  13908   2.346 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.056           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.137           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.092           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.246           ms/op
ClientSimple.existUser                      sample  16414   1.948 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.827           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.837           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.492           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.692           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.441           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.551           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.704           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.715           ms/op
ClientSimple.getUser                        sample  15970   2.043 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.594           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.891           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.381           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.178           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.197           ms/op
ClientSimple.listUser                       sample   9156   3.492 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.214           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.473           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.654           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.201           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.350           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.615           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.615           ms/op

Benchmark result is saved to 1717157760106.json
