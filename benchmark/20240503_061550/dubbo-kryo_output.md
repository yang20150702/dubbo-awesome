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
# Warmup Iteration   1: 1.956 ops/ms
Iteration   1: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.041 ops/ms


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
# Warmup Iteration   1: 5.448 ops/ms
Iteration   1: 11.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.625 ops/ms


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
# Warmup Iteration   1: 5.360 ops/ms
Iteration   1: 12.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.020 ops/ms


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
# Warmup Iteration   1: 5.041 ops/ms
Iteration   1: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.521 ops/ms


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.075 ms/op
Iteration   1: 2.090 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.090 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.066 ms/op
Iteration   1: 1.985 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.985 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.053 ms/op
Iteration   1: 2.213 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.213 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.122 ms/op
Iteration   1: 3.396 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.396 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.093 ms/op
Iteration   1: 2.044 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   1.833 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.893 ms/op
                 createUser·p0.99:   5.568 ms/op
                 createUser·p0.999:  19.560 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16036
  mean =      2.044 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14506 
    [ 2.500,  5.000) = 1266 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.893 ms/op
     p(99.0000) =      5.568 ms/op
     p(99.9000) =     19.560 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.074 ms/op
Iteration   1: 1.966 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   1.755 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.792 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  32.768 ms/op
                 existUser·p0.9999: 33.299 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16348
  mean =      1.966 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14839 
    [ 2.500,  5.000) = 1389 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.792 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =     32.768 ms/op
     p(99.9900) =     33.299 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 3.371 ±(99.9%) 0.090 ms/op
Iteration   1: 2.176 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.675 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  14.238 ms/op
                 getUser·p0.9999: 14.346 ms/op
                 getUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14720
  mean =      2.176 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 12281 
    [ 2.500,  3.750) = 1764 
    [ 3.750,  5.000) = 164 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     14.346 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.994 ±(99.9%) 0.129 ms/op
Iteration   1: 3.930 ±(99.9%) 0.069 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.881 ms/op
                 listUser·p0.99:   6.177 ms/op
                 listUser·p0.999:  31.401 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8143
  mean =      3.930 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 350 
    [ 2.500,  5.000) = 7492 
    [ 5.000,  7.500) = 237 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.881 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     31.401 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.041          ops/ms
ClientSimple.existUser                       thrpt         11.625          ops/ms
ClientSimple.getUser                         thrpt         12.020          ops/ms
ClientSimple.listUser                        thrpt          8.521          ops/ms
ClientSimple.createUser                       avgt          2.090           ms/op
ClientSimple.existUser                        avgt          1.985           ms/op
ClientSimple.getUser                          avgt          2.213           ms/op
ClientSimple.listUser                         avgt          3.396           ms/op
ClientSimple.createUser                     sample  16036   2.044 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.658           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.833           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.893           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.568           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.560           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.873           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.873           ms/op
ClientSimple.existUser                      sample  16348   1.966 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.507           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.755           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.792           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.994           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.768           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.299           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.423           ms/op
ClientSimple.getUser                        sample  14720   2.176 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.484           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.154           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.660           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.238           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.346           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.385           ms/op
ClientSimple.listUser                       sample   8143   3.930 ± 0.069   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.925           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.891           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.881           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.177           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.401           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.260           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.260           ms/op

Benchmark result is saved to 1714716713773.json
