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
# Warmup Iteration   1: 1.463 ops/ms
Iteration   1: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.153 ops/ms


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
# Warmup Iteration   1: 6.519 ops/ms
Iteration   1: 10.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.262 ops/ms


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
# Warmup Iteration   1: 6.007 ops/ms
Iteration   1: 13.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.803 ops/ms


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
# Warmup Iteration   1: 5.024 ops/ms
Iteration   1: 8.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.290 ops/ms


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.072 ms/op
Iteration   1: 2.189 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.189 ms/op


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
# Warmup Iteration   1: 3.474 ±(99.9%) 0.052 ms/op
Iteration   1: 1.784 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.784 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.093 ms/op
Iteration   1: 1.780 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.780 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.092 ms/op
Iteration   1: 3.105 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.105 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.132 ms/op
Iteration   1: 2.217 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.617 ms/op
                 createUser·p0.95:   2.950 ms/op
                 createUser·p0.99:   6.118 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14414
  mean =      2.217 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12236 
    [ 2.500,  5.000) = 1940 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.950 ms/op
     p(99.0000) =      6.118 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 2.826 ±(99.9%) 0.069 ms/op
Iteration   1: 1.808 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.089 ms/op
                 existUser·p0.95:   2.339 ms/op
                 existUser·p0.99:   3.339 ms/op
                 existUser·p0.999:  12.899 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17691
  mean =      1.808 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 16998 
    [ 2.500,  3.750) = 385 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.089 ms/op
     p(95.0000) =      2.339 ms/op
     p(99.0000) =      3.339 ms/op
     p(99.9000) =     12.899 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.075 ms/op
Iteration   1: 1.751 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   1.647 ms/op
                 getUser·p0.90:   2.109 ms/op
                 getUser·p0.95:   2.269 ms/op
                 getUser·p0.99:   2.824 ms/op
                 getUser·p0.999:  11.186 ms/op
                 getUser·p0.9999: 11.780 ms/op
                 getUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18264
  mean =      1.751 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 17761 
    [ 2.500,  3.750) = 340 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.109 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      2.824 ms/op
     p(99.9000) =     11.186 ms/op
     p(99.9900) =     11.780 ms/op
     p(99.9990) =     11.780 ms/op
     p(99.9999) =     11.780 ms/op
    p(100.0000) =     11.780 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.161 ms/op
Iteration   1: 3.552 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.870 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8989
  mean =      3.552 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1091 
    [ 2.500,  3.750) = 4582 
    [ 3.750,  5.000) = 2896 
    [ 5.000,  6.250) = 187 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.870 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.153          ops/ms
ClientSimple.existUser                       thrpt         10.262          ops/ms
ClientSimple.getUser                         thrpt         13.803          ops/ms
ClientSimple.listUser                        thrpt          8.290          ops/ms
ClientSimple.createUser                       avgt          2.189           ms/op
ClientSimple.existUser                        avgt          1.784           ms/op
ClientSimple.getUser                          avgt          1.780           ms/op
ClientSimple.listUser                         avgt          3.105           ms/op
ClientSimple.createUser                     sample  14414   2.217 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.950           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.118           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.103           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.396           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.396           ms/op
ClientSimple.existUser                      sample  17691   1.808 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.586           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.089           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.339           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.899           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.943           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.943           ms/op
ClientSimple.getUser                        sample  18264   1.751 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.745           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.647           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.824           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.186           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.780           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.780           ms/op
ClientSimple.listUser                       sample   8989   3.552 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.975           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.870           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.307           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.042           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.105           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.105           ms/op

Benchmark result is saved to 1725106590787.json
