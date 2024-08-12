# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.888 ops/ms
Iteration   1: 6.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.718 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.354 ops/ms
Iteration   1: 14.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.253 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 11.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.532 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.776 ops/ms
Iteration   1: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.463 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.089 ms/op
Iteration   1: 1.876 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.041 ±(99.9%) 0.048 ms/op
Iteration   1: 1.811 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ±(99.9%) 0.045 ms/op
Iteration   1: 1.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.835 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.073 ms/op
Iteration   1: 3.392 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.096 ms/op
Iteration   1: 1.979 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   1.821 ms/op
                 createUser·p0.90:   2.286 ms/op
                 createUser·p0.95:   2.564 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 23.099 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16155
  mean =      1.979 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15196 
    [ 2.500,  5.000) = 800 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     23.099 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ±(99.9%) 0.078 ms/op
Iteration   1: 2.092 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.007 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  21.517 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15347
  mean =      2.092 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13882 
    [ 2.500,  5.000) = 1333 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     21.517 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.239 ±(99.9%) 0.090 ms/op
Iteration   1: 1.917 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   1.712 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.765 ms/op
                 getUser·p0.99:   4.740 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 24.388 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16830
  mean =      1.917 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15517 
    [ 2.500,  5.000) = 1155 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      4.740 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     24.388 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ±(99.9%) 0.165 ms/op
Iteration   1: 3.398 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.240 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 13.451 ms/op
                 listUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9428
  mean =      3.398 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 809 
    [ 2.500,  3.750) = 5750 
    [ 3.750,  5.000) = 2539 
    [ 5.000,  6.250) = 189 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.451 ms/op
    p(100.0000) =     13.451 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.718          ops/ms
ClientSimple.existUser                       thrpt         14.253          ops/ms
ClientSimple.getUser                         thrpt         11.532          ops/ms
ClientSimple.listUser                        thrpt          8.463          ops/ms
ClientSimple.createUser                       avgt          1.876           ms/op
ClientSimple.existUser                        avgt          1.811           ms/op
ClientSimple.getUser                          avgt          1.835           ms/op
ClientSimple.listUser                         avgt          3.392           ms/op
ClientSimple.createUser                     sample  16155   1.979 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.560           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.821           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.915           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.152           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.099           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.462           ms/op
ClientSimple.existUser                      sample  15347   2.092 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.587           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.735           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.517           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.315           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.315           ms/op
ClientSimple.getUser                        sample  16830   1.917 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.712           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.740           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.248           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.388           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.478           ms/op
ClientSimple.listUser                       sample   9428   3.398 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.944           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.240           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.750           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.418           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.451           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.451           ms/op

Benchmark result is saved to 1723465159044.json
