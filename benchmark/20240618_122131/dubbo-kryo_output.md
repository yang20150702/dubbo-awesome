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
# Warmup Iteration   1: 2.310 ops/ms
Iteration   1: 7.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.313 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ops/ms
Iteration   1: 12.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.453 ops/ms


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
# Warmup Iteration   1: 5.699 ops/ms
Iteration   1: 13.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.103 ops/ms


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
# Warmup Iteration   1: 5.401 ops/ms
Iteration   1: 8.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.318 ops/ms


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.082 ms/op
Iteration   1: 2.119 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.119 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.073 ms/op
Iteration   1: 2.060 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.060 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ±(99.9%) 0.050 ms/op
Iteration   1: 1.892 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.892 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ±(99.9%) 0.153 ms/op
Iteration   1: 3.511 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.511 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ±(99.9%) 0.081 ms/op
Iteration   1: 2.101 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.488 ms/op
                 createUser·p0.50:   1.927 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  19.286 ms/op
                 createUser·p0.9999: 20.138 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15216
  mean =      2.101 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13095 
    [ 2.500,  5.000) = 2004 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     19.286 ms/op
     p(99.9900) =     20.138 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.078 ms/op
Iteration   1: 1.879 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  12.089 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17045
  mean =      1.879 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 16065 
    [ 2.500,  3.750) = 596 
    [ 3.750,  5.000) = 128 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =     12.089 ms/op
     p(99.9900) =     12.255 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.077 ms/op
Iteration   1: 2.170 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  10.884 ms/op
                 getUser·p0.9999: 11.407 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14710
  mean =      2.170 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 12687 
    [ 2.500,  3.750) = 1782 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     10.884 ms/op
     p(99.9900) =     11.407 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.135 ms/op
Iteration   1: 3.285 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.318 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  7.024 ms/op
                 listUser·p0.9999: 7.823 ms/op
                 listUser·p1.00:   7.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9765
  mean =      3.285 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 33 
    [1.500, 2.000) = 361 
    [2.000, 2.500) = 1272 
    [2.500, 3.000) = 1831 
    [3.000, 3.500) = 2474 
    [3.500, 4.000) = 2488 
    [4.000, 4.500) = 773 
    [4.500, 5.000) = 243 
    [5.000, 5.500) = 117 
    [5.500, 6.000) = 86 
    [6.000, 6.500) = 48 
    [6.500, 7.000) = 26 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =      7.024 ms/op
     p(99.9900) =      7.823 ms/op
     p(99.9990) =      7.823 ms/op
     p(99.9999) =      7.823 ms/op
    p(100.0000) =      7.823 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.313          ops/ms
ClientSimple.existUser                       thrpt         12.453          ops/ms
ClientSimple.getUser                         thrpt         13.103          ops/ms
ClientSimple.listUser                        thrpt          8.318          ops/ms
ClientSimple.createUser                       avgt          2.119           ms/op
ClientSimple.existUser                        avgt          2.060           ms/op
ClientSimple.getUser                          avgt          1.892           ms/op
ClientSimple.listUser                         avgt          3.511           ms/op
ClientSimple.createUser                     sample  15216   2.101 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.488           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.927           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.375           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.286           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.138           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  17045   1.879 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.630           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.985           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.089           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.255           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.255           ms/op
ClientSimple.getUser                        sample  14710   2.170 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.666           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.884           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.407           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.731           ms/op
ClientSimple.listUser                       sample   9765   3.285 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.950           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.318           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.024           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.823           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.823           ms/op

Benchmark result is saved to 1718713013919.json
