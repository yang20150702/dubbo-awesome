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
# Warmup Iteration   1: 1.718 ops/ms
Iteration   1: 7.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.323 ops/ms


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
# Warmup Iteration   1: 6.848 ops/ms
Iteration   1: 13.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.122 ops/ms


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
# Warmup Iteration   1: 4.369 ops/ms
Iteration   1: 12.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.573 ops/ms


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
# Warmup Iteration   1: 5.148 ops/ms
Iteration   1: 8.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.069 ops/ms


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.079 ms/op
Iteration   1: 2.097 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ±(99.9%) 0.046 ms/op
Iteration   1: 2.029 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.029 ms/op


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
# Warmup Iteration   1: 3.595 ±(99.9%) 0.070 ms/op
Iteration   1: 2.197 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.197 ms/op


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.091 ms/op
Iteration   1: 3.335 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.335 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.095 ms/op
Iteration   1: 2.005 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.806 ms/op
                 createUser·p0.99:   3.557 ms/op
                 createUser·p0.999:  12.797 ms/op
                 createUser·p0.9999: 13.047 ms/op
                 createUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15941
  mean =      2.005 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 209 
    [ 1.250,  2.500) = 13271 
    [ 2.500,  3.750) = 2317 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.557 ms/op
     p(99.9000) =     12.797 ms/op
     p(99.9900) =     13.047 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.214 ms/op
Iteration   1: 2.052 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.278 ms/op
                 existUser·p0.50:   1.866 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   5.888 ms/op
                 existUser·p0.999:  35.811 ms/op
                 existUser·p0.9999: 36.787 ms/op
                 existUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15574
  mean =      2.052 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14220 
    [ 2.500,  5.000) = 1151 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      5.888 ms/op
     p(99.9000) =     35.811 ms/op
     p(99.9900) =     36.787 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 3.538 ±(99.9%) 0.100 ms/op
Iteration   1: 1.979 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.367 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.437 ms/op
                 getUser·p0.999:  19.650 ms/op
                 getUser·p0.9999: 19.959 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16322
  mean =      1.979 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15347 
    [ 2.500,  5.000) = 927 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.437 ms/op
     p(99.9000) =     19.650 ms/op
     p(99.9900) =     19.959 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.139 ms/op
Iteration   1: 3.841 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   5.995 ms/op
                 listUser·p0.999:  20.634 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8323
  mean =      3.841 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 156 
    [ 2.500,  5.000) = 7747 
    [ 5.000,  7.500) = 387 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      5.995 ms/op
     p(99.9000) =     20.634 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.323          ops/ms
ClientSimple.existUser                       thrpt         13.122          ops/ms
ClientSimple.getUser                         thrpt         12.573          ops/ms
ClientSimple.listUser                        thrpt          8.069          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          2.029           ms/op
ClientSimple.getUser                          avgt          2.197           ms/op
ClientSimple.listUser                         avgt          3.335           ms/op
ClientSimple.createUser                     sample  15941   2.005 ± 0.020   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.750           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.557           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.797           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.047           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.222           ms/op
ClientSimple.existUser                      sample  15574   2.052 ± 0.045   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.278           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.866           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.888           ms/op
ClientSimple.existUser:existUser·p0.999     sample         35.811           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         36.787           ms/op
ClientSimple.existUser:existUser·p1.00      sample         36.897           ms/op
ClientSimple.getUser                        sample  16322   1.979 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.896           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.437           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.650           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.959           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.021           ms/op
ClientSimple.listUser                       sample   8323   3.841 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.255           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.005           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.995           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.634           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.053           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.053           ms/op

Benchmark result is saved to 1716251968325.json
