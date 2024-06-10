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
# Warmup Iteration   1: 1.428 ops/ms
Iteration   1: 6.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.292 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.816 ops/ms
Iteration   1: 11.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.114 ops/ms


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
# Warmup Iteration   1: 5.484 ops/ms
Iteration   1: 11.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.435 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ops/ms
Iteration   1: 8.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.137 ops/ms


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.088 ms/op
Iteration   1: 2.317 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.317 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.065 ms/op
Iteration   1: 1.962 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.962 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.925 ±(99.9%) 0.084 ms/op
Iteration   1: 2.505 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.505 ms/op


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.135 ms/op
Iteration   1: 3.787 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.787 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.101 ms/op
Iteration   1: 2.339 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.333 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  18.721 ms/op
                 createUser·p0.9999: 19.473 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13682
  mean =      2.339 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 11022 
    [ 2.500,  3.750) = 2169 
    [ 3.750,  5.000) = 198 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.333 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     18.721 ms/op
     p(99.9900) =     19.473 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.095 ms/op
Iteration   1: 1.930 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   1.808 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  12.609 ms/op
                 existUser·p0.9999: 12.807 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16696
  mean =      1.930 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 15638 
    [ 2.500,  3.750) = 861 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =     12.609 ms/op
     p(99.9900) =     12.807 ms/op
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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.106 ms/op
Iteration   1: 2.298 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   2.183 ms/op
                 getUser·p0.90:   2.874 ms/op
                 getUser·p0.95:   3.149 ms/op
                 getUser·p0.99:   5.695 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 12.734 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13942
  mean =      2.298 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 10541 
    [ 2.500,  3.750) = 3005 
    [ 3.750,  5.000) = 128 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.874 ms/op
     p(95.0000) =      3.149 ms/op
     p(99.0000) =      5.695 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     12.734 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 5.934 ±(99.9%) 0.224 ms/op
Iteration   1: 3.787 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.423 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  17.025 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8447
  mean =      3.787 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 253 
    [ 2.500,  3.750) = 4294 
    [ 3.750,  5.000) = 3052 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     17.025 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.292          ops/ms
ClientSimple.existUser                       thrpt         11.114          ops/ms
ClientSimple.getUser                         thrpt         11.435          ops/ms
ClientSimple.listUser                        thrpt          8.137          ops/ms
ClientSimple.createUser                       avgt          2.317           ms/op
ClientSimple.existUser                        avgt          1.962           ms/op
ClientSimple.getUser                          avgt          2.505           ms/op
ClientSimple.listUser                         avgt          3.787           ms/op
ClientSimple.createUser                     sample  13682   2.339 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.415           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.333           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.700           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.721           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.473           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.497           ms/op
ClientSimple.existUser                      sample  16696   1.930 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.958           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.808           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.719           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.609           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.807           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.829           ms/op
ClientSimple.getUser                        sample  13942   2.298 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.504           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.874           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.149           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.695           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.764           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.734           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.747           ms/op
ClientSimple.listUser                       sample   8447   3.787 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.423           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.637           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.521           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.766           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.025           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.564           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.564           ms/op

Benchmark result is saved to 1718021806745.json
