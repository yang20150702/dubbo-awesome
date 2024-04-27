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
# Warmup Iteration   1: 1.665 ops/ms
Iteration   1: 6.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.295 ops/ms


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
# Warmup Iteration   1: 5.495 ops/ms
Iteration   1: 12.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.160 ops/ms


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
# Warmup Iteration   1: 5.433 ops/ms
Iteration   1: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.863 ops/ms


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
# Warmup Iteration   1: 4.428 ops/ms
Iteration   1: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.685 ops/ms


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.074 ms/op
Iteration   1: 2.184 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.184 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.053 ms/op
Iteration   1: 2.137 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.137 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.066 ms/op
Iteration   1: 1.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.835 ms/op


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
# Warmup Iteration   1: 5.222 ±(99.9%) 0.112 ms/op
Iteration   1: 3.545 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.545 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.094 ms/op
Iteration   1: 2.446 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.353 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  38.797 ms/op
                 createUser·p0.9999: 39.148 ms/op
                 createUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13269
  mean =      2.446 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9460 
    [ 2.500,  5.000) = 3501 
    [ 5.000,  7.500) = 234 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.353 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     38.797 ms/op
     p(99.9900) =     39.148 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 2.785 ±(99.9%) 0.061 ms/op
Iteration   1: 1.960 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.225 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 12.580 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16312
  mean =      1.960 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 451 
    [ 1.250,  2.500) = 14372 
    [ 2.500,  3.750) = 1286 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.580 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.085 ms/op
Iteration   1: 2.113 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   3.325 ms/op
                 getUser·p0.999:  20.276 ms/op
                 getUser·p0.9999: 21.610 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15115
  mean =      2.113 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12618 
    [ 2.500,  5.000) = 2428 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.325 ms/op
     p(99.9000) =     20.276 ms/op
     p(99.9900) =     21.610 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.138 ms/op
Iteration   1: 3.345 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.025 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9571
  mean =      3.345 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 768 
    [ 2.500,  5.000) = 8429 
    [ 5.000,  7.500) = 300 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.025 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.295          ops/ms
ClientSimple.existUser                       thrpt         12.160          ops/ms
ClientSimple.getUser                         thrpt         12.863          ops/ms
ClientSimple.listUser                        thrpt          8.685          ops/ms
ClientSimple.createUser                       avgt          2.184           ms/op
ClientSimple.existUser                        avgt          2.137           ms/op
ClientSimple.getUser                          avgt          1.835           ms/op
ClientSimple.listUser                         avgt          3.545           ms/op
ClientSimple.createUser                     sample  13269   2.446 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.792           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.353           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.275           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.797           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.148           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.191           ms/op
ClientSimple.existUser                      sample  16312   1.960 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.225           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.227           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.042           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.580           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.829           ms/op
ClientSimple.getUser                        sample  15115   2.113 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.692           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.325           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.276           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.610           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.627           ms/op
ClientSimple.listUser                       sample   9571   3.345 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.015           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.025           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.447           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.150           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.150           ms/op

Benchmark result is saved to 1714219996004.json
