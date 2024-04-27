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
# Warmup Iteration   1: 1.820 ops/ms
Iteration   1: 7.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.260 ops/ms


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
# Warmup Iteration   1: 6.214 ops/ms
Iteration   1: 11.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.677 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.855 ops/ms
Iteration   1: 14.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.047 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.908 ops/ms
Iteration   1: 9.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.314 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ±(99.9%) 0.074 ms/op
Iteration   1: 1.963 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.963 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ±(99.9%) 0.045 ms/op
Iteration   1: 1.882 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.882 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.047 ms/op
Iteration   1: 1.872 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.872 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.088 ms/op
Iteration   1: 3.487 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.076 ms/op
Iteration   1: 2.319 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   2.245 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   4.761 ms/op
                 createUser·p0.999:  28.941 ms/op
                 createUser·p0.9999: 32.329 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13894
  mean =      2.319 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9752 
    [ 2.500,  5.000) = 4012 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.761 ms/op
     p(99.9000) =     28.941 ms/op
     p(99.9900) =     32.329 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ±(99.9%) 0.078 ms/op
Iteration   1: 1.835 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.140 ms/op
                 existUser·p0.999:  10.617 ms/op
                 existUser·p0.9999: 11.222 ms/op
                 existUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17436
  mean =      1.835 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 947 
    [ 1.250,  2.500) = 15856 
    [ 2.500,  3.750) = 519 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.140 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     11.222 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ±(99.9%) 0.114 ms/op
Iteration   1: 1.904 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   1.698 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  35.468 ms/op
                 getUser·p0.9999: 36.414 ms/op
                 getUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16796
  mean =      1.904 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15351 
    [ 2.500,  5.000) = 1354 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =     35.468 ms/op
     p(99.9900) =     36.414 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.103 ms/op
Iteration   1: 3.132 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.831 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   4.915 ms/op
                 listUser·p0.999:  14.349 ms/op
                 listUser·p0.9999: 15.328 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10205
  mean =      3.132 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 1199 
    [ 2.500,  3.750) = 7762 
    [ 3.750,  5.000) = 1141 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.831 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     14.349 ms/op
     p(99.9900) =     15.328 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.260          ops/ms
ClientSimple.existUser                       thrpt         11.677          ops/ms
ClientSimple.getUser                         thrpt         14.047          ops/ms
ClientSimple.listUser                        thrpt          9.314          ops/ms
ClientSimple.createUser                       avgt          1.963           ms/op
ClientSimple.existUser                        avgt          1.882           ms/op
ClientSimple.getUser                          avgt          1.872           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  13894   2.319 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.563           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.245           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.761           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.941           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.329           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.342           ms/op
ClientSimple.existUser                      sample  17436   1.835 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.677           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.140           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.617           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.222           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.551           ms/op
ClientSimple.getUser                        sample  16796   1.904 ± 0.043   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.566           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.698           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.026           ms/op
ClientSimple.getUser:getUser·p0.999         sample         35.468           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         36.414           ms/op
ClientSimple.getUser:getUser·p1.00          sample         36.504           ms/op
ClientSimple.listUser                       sample  10205   3.132 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.905           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.002           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.831           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.349           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.328           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.335           ms/op

Benchmark result is saved to 1714178257772.json
