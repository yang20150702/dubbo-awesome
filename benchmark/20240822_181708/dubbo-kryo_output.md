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
# Warmup Iteration   1: 1.547 ops/ms
Iteration   1: 5.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.876 ops/ms


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
# Warmup Iteration   1: 5.177 ops/ms
Iteration   1: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.696 ops/ms


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
# Warmup Iteration   1: 5.103 ops/ms
Iteration   1: 10.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.757 ops/ms


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
# Warmup Iteration   1: 4.242 ops/ms
Iteration   1: 8.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.786 ops/ms


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.059 ms/op
Iteration   1: 2.040 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.040 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.047 ms/op
Iteration   1: 1.926 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.926 ms/op


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
# Warmup Iteration   1: 3.384 ±(99.9%) 0.059 ms/op
Iteration   1: 2.153 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.153 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.077 ms/op
Iteration   1: 3.525 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.525 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.088 ms/op
Iteration   1: 2.230 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.306 ms/op
                 createUser·p0.50:   2.044 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   7.207 ms/op
                 createUser·p0.999:  23.776 ms/op
                 createUser·p0.9999: 27.969 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14409
  mean =      2.230 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10869 
    [ 2.500,  5.000) = 3267 
    [ 5.000,  7.500) = 139 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.306 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      7.207 ms/op
     p(99.9000) =     23.776 ms/op
     p(99.9900) =     27.969 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 3.277 ±(99.9%) 0.074 ms/op
Iteration   1: 1.886 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   3.919 ms/op
                 existUser·p0.999:  21.856 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17003
  mean =      1.886 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15574 
    [ 2.500,  5.000) = 1360 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      3.919 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.087 ms/op
Iteration   1: 2.079 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.630 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  12.112 ms/op
                 getUser·p0.9999: 12.947 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15383
  mean =      2.079 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 14041 
    [ 2.500,  3.750) = 1167 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =     12.112 ms/op
     p(99.9900) =     12.947 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.140 ms/op
Iteration   1: 3.491 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.695 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.257 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.706 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9163
  mean =      3.491 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1057 
    [ 2.500,  3.750) = 5521 
    [ 3.750,  5.000) = 2176 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.257 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     16.706 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.876          ops/ms
ClientSimple.existUser                       thrpt         10.696          ops/ms
ClientSimple.getUser                         thrpt         10.757          ops/ms
ClientSimple.listUser                        thrpt          8.786          ops/ms
ClientSimple.createUser                       avgt          2.040           ms/op
ClientSimple.existUser                        avgt          1.926           ms/op
ClientSimple.getUser                          avgt          2.153           ms/op
ClientSimple.listUser                         avgt          3.525           ms/op
ClientSimple.createUser                     sample  14409   2.230 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.306           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.044           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.776           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.969           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.984           ms/op
ClientSimple.existUser                      sample  17003   1.886 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.919           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.856           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.020           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.020           ms/op
ClientSimple.getUser                        sample  15383   2.079 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.869           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.584           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.112           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.947           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.353           ms/op
ClientSimple.listUser                       sample   9163   3.491 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.695           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.257           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.733           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.706           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.760           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.760           ms/op

Benchmark result is saved to 1724350371929.json
