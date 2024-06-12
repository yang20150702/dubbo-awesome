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
# Warmup Iteration   1: 1.473 ops/ms
Iteration   1: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.415 ops/ms


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
# Warmup Iteration   1: 5.824 ops/ms
Iteration   1: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.761 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ops/ms
Iteration   1: 10.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.993 ops/ms


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
# Warmup Iteration   1: 3.980 ops/ms
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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.082 ms/op
Iteration   1: 2.115 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ±(99.9%) 0.060 ms/op
Iteration   1: 2.142 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.142 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.075 ms/op
Iteration   1: 2.104 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.104 ms/op


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.125 ms/op
Iteration   1: 3.745 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.745 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.082 ms/op
Iteration   1: 2.161 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   1.892 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   11.635 ms/op
                 createUser·p0.999:  32.604 ms/op
                 createUser·p0.9999: 33.489 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14791
  mean =      2.161 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13614 
    [ 2.500,  5.000) = 897 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =     11.635 ms/op
     p(99.9000) =     32.604 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 3.200 ±(99.9%) 0.078 ms/op
Iteration   1: 1.866 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.257 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 12.179 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17373
  mean =      1.866 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 16512 
    [ 2.500,  3.750) = 392 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.257 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     12.179 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.096 ms/op
Iteration   1: 1.981 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  23.423 ms/op
                 getUser·p0.9999: 24.114 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16198
  mean =      1.981 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14833 
    [ 2.500,  5.000) = 1228 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     23.423 ms/op
     p(99.9900) =     24.114 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.115 ms/op
Iteration   1: 3.875 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   5.637 ms/op
                 listUser·p0.999:  6.344 ms/op
                 listUser·p0.9999: 7.537 ms/op
                 listUser·p1.00:   7.537 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8264
  mean =      3.875 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 36 
    [2.000, 2.500) = 143 
    [2.500, 3.000) = 693 
    [3.000, 3.500) = 1062 
    [3.500, 4.000) = 2951 
    [4.000, 4.500) = 2048 
    [4.500, 5.000) = 1000 
    [5.000, 5.500) = 221 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 38 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      5.637 ms/op
     p(99.9000) =      6.344 ms/op
     p(99.9900) =      7.537 ms/op
     p(99.9990) =      7.537 ms/op
     p(99.9999) =      7.537 ms/op
    p(100.0000) =      7.537 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.415          ops/ms
ClientSimple.existUser                       thrpt         10.761          ops/ms
ClientSimple.getUser                         thrpt         10.993          ops/ms
ClientSimple.listUser                        thrpt          8.825          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          2.142           ms/op
ClientSimple.getUser                          avgt          2.104           ms/op
ClientSimple.listUser                         avgt          3.745           ms/op
ClientSimple.createUser                     sample  14791   2.161 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.520           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.892           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.635           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.604           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.489           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.489           ms/op
ClientSimple.existUser                      sample  17373   1.866 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.645           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.257           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.682           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.179           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.288           ms/op
ClientSimple.getUser                        sample  16198   1.981 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.553           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.874           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.423           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.114           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.216           ms/op
ClientSimple.listUser                       sample   8264   3.875 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.947           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.637           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.344           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.537           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.537           ms/op

Benchmark result is saved to 1718215993131.json
