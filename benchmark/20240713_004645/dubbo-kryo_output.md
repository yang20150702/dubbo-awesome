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
# Warmup Iteration   1: 2.224 ops/ms
Iteration   1: 7.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.678 ops/ms


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
# Warmup Iteration   1: 5.307 ops/ms
Iteration   1: 14.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.626 ops/ms


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
# Warmup Iteration   1: 5.756 ops/ms
Iteration   1: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.871 ops/ms


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
# Warmup Iteration   1: 5.512 ops/ms
Iteration   1: 8.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.345 ops/ms


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.102 ms/op
Iteration   1: 2.269 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.269 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.060 ms/op
Iteration   1: 2.043 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.043 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.061 ms/op
Iteration   1: 2.026 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.026 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.094 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.221 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.083 ms/op
Iteration   1: 2.190 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  37.552 ms/op
                 createUser·p0.9999: 38.505 ms/op
                 createUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14599
  mean =      2.190 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13097 
    [ 2.500,  5.000) = 1251 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     37.552 ms/op
     p(99.9900) =     38.505 ms/op
     p(99.9990) =     38.535 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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
# Warmup Iteration   1: 2.915 ±(99.9%) 0.065 ms/op
Iteration   1: 1.897 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   3.467 ms/op
                 existUser·p0.999:  15.172 ms/op
                 existUser·p0.9999: 15.273 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16850
  mean =      1.897 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 452 
    [ 1.250,  2.500) = 15572 
    [ 2.500,  3.750) = 679 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      3.467 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     15.273 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.090 ms/op
Iteration   1: 2.176 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  15.139 ms/op
                 getUser·p0.9999: 15.699 ms/op
                 getUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14720
  mean =      2.176 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 12578 
    [ 2.500,  3.750) = 1919 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     15.699 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 4.549 ±(99.9%) 0.142 ms/op
Iteration   1: 3.370 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.322 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.013 ms/op
                 listUser·p0.999:  7.954 ms/op
                 listUser·p0.9999: 8.585 ms/op
                 listUser·p1.00:   8.585 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9487
  mean =      3.370 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 247 
    [2.000, 2.500) = 1195 
    [2.500, 3.000) = 2014 
    [3.000, 3.500) = 1995 
    [3.500, 4.000) = 2481 
    [4.000, 4.500) = 782 
    [4.500, 5.000) = 277 
    [5.000, 5.500) = 184 
    [5.500, 6.000) = 128 
    [6.000, 6.500) = 43 
    [6.500, 7.000) = 33 
    [7.000, 7.500) = 57 
    [7.500, 8.000) = 32 
    [8.000, 8.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.013 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =      8.585 ms/op
     p(99.9990) =      8.585 ms/op
     p(99.9999) =      8.585 ms/op
    p(100.0000) =      8.585 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.678          ops/ms
ClientSimple.existUser                       thrpt         14.626          ops/ms
ClientSimple.getUser                         thrpt         12.871          ops/ms
ClientSimple.listUser                        thrpt          8.345          ops/ms
ClientSimple.createUser                       avgt          2.269           ms/op
ClientSimple.existUser                        avgt          2.043           ms/op
ClientSimple.getUser                          avgt          2.026           ms/op
ClientSimple.listUser                         avgt          3.221           ms/op
ClientSimple.createUser                     sample  14599   2.190 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.513           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.233           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.552           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.505           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.535           ms/op
ClientSimple.existUser                      sample  16850   1.897 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.382           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.467           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.172           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.273           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.352           ms/op
ClientSimple.getUser                        sample  14720   2.176 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.565           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.912           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.139           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.699           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.892           ms/op
ClientSimple.listUser                       sample   9487   3.370 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.867           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.322           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.022           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.013           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.954           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.585           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.585           ms/op

Benchmark result is saved to 1720831342323.json
