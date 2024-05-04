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
# Warmup Iteration   1: 1.315 ops/ms
Iteration   1: 5.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.572 ops/ms


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
# Warmup Iteration   1: 5.233 ops/ms
Iteration   1: 11.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.201 ops/ms


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
# Warmup Iteration   1: 4.897 ops/ms
Iteration   1: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.879 ops/ms


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
# Warmup Iteration   1: 3.977 ops/ms
Iteration   1: 7.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.772 ops/ms


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.073 ms/op
Iteration   1: 2.253 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.253 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.045 ms/op
Iteration   1: 2.053 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.053 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.062 ms/op
Iteration   1: 2.083 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.083 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.098 ms/op
Iteration   1: 3.710 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.710 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.091 ms/op
Iteration   1: 2.231 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   5.671 ms/op
                 createUser·p0.999:  26.040 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14318
  mean =      2.231 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11334 
    [ 2.500,  5.000) = 2782 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.318 ms/op
     p(99.0000) =      5.671 ms/op
     p(99.9000) =     26.040 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.095 ms/op
Iteration   1: 1.675 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   1.528 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  16.865 ms/op
                 existUser·p0.9999: 17.046 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19327
  mean =      1.675 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1124 
    [ 1.250,  2.500) = 17736 
    [ 2.500,  3.750) = 301 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      1.528 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     16.865 ms/op
     p(99.9900) =     17.046 ms/op
     p(99.9990) =     17.138 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.097 ms/op
Iteration   1: 2.245 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.839 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  21.420 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14315
  mean =      2.245 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11232 
    [ 2.500,  5.000) = 2914 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     21.420 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 4.549 ±(99.9%) 0.133 ms/op
Iteration   1: 3.748 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.050 ms/op
                 listUser·p0.999:  7.643 ms/op
                 listUser·p0.9999: 10.174 ms/op
                 listUser·p1.00:   10.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8546
  mean =      3.748 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 30 
    [ 2.000,  3.000) = 1127 
    [ 3.000,  4.000) = 4372 
    [ 4.000,  5.000) = 2772 
    [ 5.000,  6.000) = 156 
    [ 6.000,  7.000) = 53 
    [ 7.000,  8.000) = 33 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.050 ms/op
     p(99.9000) =      7.643 ms/op
     p(99.9900) =     10.174 ms/op
     p(99.9990) =     10.174 ms/op
     p(99.9999) =     10.174 ms/op
    p(100.0000) =     10.174 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.572          ops/ms
ClientSimple.existUser                       thrpt         11.201          ops/ms
ClientSimple.getUser                         thrpt          9.879          ops/ms
ClientSimple.listUser                        thrpt          7.772          ops/ms
ClientSimple.createUser                       avgt          2.253           ms/op
ClientSimple.existUser                        avgt          2.053           ms/op
ClientSimple.getUser                          avgt          2.083           ms/op
ClientSimple.listUser                         avgt          3.710           ms/op
ClientSimple.createUser                     sample  14318   2.231 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.547           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.318           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.671           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.040           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.214           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.214           ms/op
ClientSimple.existUser                      sample  19327   1.675 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.805           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.528           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.367           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.865           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.046           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.138           ms/op
ClientSimple.getUser                        sample  14315   2.245 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.224           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.292           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.420           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.884           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.983           ms/op
ClientSimple.listUser                       sample   8546   3.748 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.257           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.711           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.050           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.643           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.174           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.174           ms/op

Benchmark result is saved to 1714803032032.json
