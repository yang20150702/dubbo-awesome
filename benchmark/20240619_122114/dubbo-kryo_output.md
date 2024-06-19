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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 6.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.858 ops/ms


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
# Warmup Iteration   1: 5.137 ops/ms
Iteration   1: 12.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.362 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.903 ops/ms


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
# Warmup Iteration   1: 5.297 ops/ms
Iteration   1: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.553 ops/ms


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.068 ms/op
Iteration   1: 1.950 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.950 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.062 ms/op
Iteration   1: 1.769 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.769 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.051 ms/op
Iteration   1: 2.034 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


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
# Warmup Iteration   1: 4.331 ±(99.9%) 0.086 ms/op
Iteration   1: 3.151 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.151 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.083 ms/op
Iteration   1: 2.242 ±(99.9%) 0.141 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   1.788 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.617 ms/op
                 createUser·p0.99:   8.510 ms/op
                 createUser·p0.999:  105.376 ms/op
                 createUser·p0.9999: 125.662 ms/op
                 createUser·p1.00:   125.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14261
  mean =      2.242 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14174 
    [ 12.500,  25.000) = 40 
    [ 25.000,  37.500) = 7 
    [ 37.500,  50.000) = 4 
    [ 50.000,  62.500) = 4 
    [ 62.500,  75.000) = 4 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 7 
    [112.500, 125.000) = 8 
    [125.000, 137.500) = 3 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      8.510 ms/op
     p(99.9000) =    105.376 ms/op
     p(99.9900) =    125.662 ms/op
     p(99.9990) =    125.829 ms/op
     p(99.9999) =    125.829 ms/op
    p(100.0000) =    125.829 ms/op


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
# Warmup Iteration   1: 2.957 ±(99.9%) 0.068 ms/op
Iteration   1: 1.824 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   3.062 ms/op
                 existUser·p0.999:  16.399 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17553
  mean =      1.824 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 483 
    [ 1.250,  2.500) = 16567 
    [ 2.500,  3.750) = 450 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.062 ms/op
     p(99.9000) =     16.399 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.070 ms/op
Iteration   1: 1.925 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   1.776 ms/op
                 getUser·p0.90:   2.359 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.574 ms/op
                 getUser·p0.999:  20.775 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16918
  mean =      1.925 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15778 
    [ 2.500,  5.000) = 988 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.574 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.121 ms/op
Iteration   1: 3.323 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.174 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.587 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9627
  mean =      3.323 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 958 
    [ 2.500,  3.750) = 6234 
    [ 3.750,  5.000) = 2152 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.587 ms/op
     p(99.9000) =     14.326 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.858          ops/ms
ClientSimple.existUser                       thrpt          12.362          ops/ms
ClientSimple.getUser                         thrpt          12.903          ops/ms
ClientSimple.listUser                        thrpt           8.553          ops/ms
ClientSimple.createUser                       avgt           1.950           ms/op
ClientSimple.existUser                        avgt           1.769           ms/op
ClientSimple.getUser                          avgt           2.034           ms/op
ClientSimple.listUser                         avgt           3.151           ms/op
ClientSimple.createUser                     sample  14261    2.242 ± 0.141   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.354           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.788           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.617           ms/op
ClientSimple.createUser:createUser·p0.99    sample           8.510           ms/op
ClientSimple.createUser:createUser·p0.999   sample         105.376           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         125.662           ms/op
ClientSimple.createUser:createUser·p1.00    sample         125.829           ms/op
ClientSimple.existUser                      sample  17553    1.824 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.612           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.376           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.062           ms/op
ClientSimple.existUser:existUser·p0.999     sample          16.399           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientSimple.existUser:existUser·p1.00      sample          17.400           ms/op
ClientSimple.getUser                        sample  16918    1.925 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.507           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.776           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.359           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.574           ms/op
ClientSimple.getUser:getUser·p0.999         sample          20.775           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          21.955           ms/op
ClientSimple.getUser:getUser·p1.00          sample          21.955           ms/op
ClientSimple.listUser                       sample   9627    3.323 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.993           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.174           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.092           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample           7.587           ms/op
ClientSimple.listUser:listUser·p0.999       sample          14.326           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          16.368           ms/op
ClientSimple.listUser:listUser·p1.00        sample          16.368           ms/op

Benchmark result is saved to 1718799408665.json
