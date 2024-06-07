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
# Warmup Iteration   1: 1.028 ops/ms
Iteration   1: 5.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.403 ops/ms


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
# Warmup Iteration   1: 6.108 ops/ms
Iteration   1: 11.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.251 ops/ms


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
# Warmup Iteration   1: 4.890 ops/ms
Iteration   1: 11.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.037 ops/ms


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
# Warmup Iteration   1: 5.057 ops/ms
Iteration   1: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.586 ops/ms


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.087 ms/op
Iteration   1: 2.132 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.132 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.054 ms/op
Iteration   1: 1.840 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.840 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.055 ms/op
Iteration   1: 1.857 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.857 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.105 ms/op
Iteration   1: 3.694 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.694 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.103 ms/op
Iteration   1: 2.197 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   8.583 ms/op
                 createUser·p0.999:  15.886 ms/op
                 createUser·p0.9999: 17.614 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14711
  mean =      2.197 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 12844 
    [ 2.500,  3.750) = 1236 
    [ 3.750,  5.000) = 236 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      8.583 ms/op
     p(99.9000) =     15.886 ms/op
     p(99.9900) =     17.614 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.073 ms/op
Iteration   1: 1.981 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.445 ms/op
                 existUser·p0.50:   1.864 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 10.171 ms/op
                 existUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16182
  mean =      1.981 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 37 
    [ 1.000,  2.000) = 10378 
    [ 2.000,  3.000) = 5379 
    [ 3.000,  4.000) = 115 
    [ 4.000,  5.000) = 82 
    [ 5.000,  6.000) = 111 
    [ 6.000,  7.000) = 32 
    [ 7.000,  8.000) = 16 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     10.171 ms/op
     p(99.9990) =     10.191 ms/op
     p(99.9999) =     10.191 ms/op
    p(100.0000) =     10.191 ms/op


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.088 ms/op
Iteration   1: 2.187 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   1.978 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 24.348 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14827
  mean =      2.187 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11288 
    [ 2.500,  5.000) = 3438 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     24.348 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.149 ms/op
Iteration   1: 3.606 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.842 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  18.155 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8878
  mean =      3.606 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 906 
    [ 2.500,  3.750) = 4347 
    [ 3.750,  5.000) = 3245 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.842 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     18.155 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.403          ops/ms
ClientSimple.existUser                       thrpt         11.251          ops/ms
ClientSimple.getUser                         thrpt         11.037          ops/ms
ClientSimple.listUser                        thrpt          9.586          ops/ms
ClientSimple.createUser                       avgt          2.132           ms/op
ClientSimple.existUser                        avgt          1.840           ms/op
ClientSimple.getUser                          avgt          1.857           ms/op
ClientSimple.listUser                         avgt          3.694           ms/op
ClientSimple.createUser                     sample  14711   2.197 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.989           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.583           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.886           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.614           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.629           ms/op
ClientSimple.existUser                      sample  16182   1.981 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.445           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.864           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.071           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.043           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.171           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.191           ms/op
ClientSimple.getUser                        sample  14827   2.187 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.534           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.978           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.064           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.235           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.822           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.348           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.379           ms/op
ClientSimple.listUser                       sample   8878   3.606 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.625           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.842           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.155           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.562           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.562           ms/op

Benchmark result is saved to 1717783978165.json
