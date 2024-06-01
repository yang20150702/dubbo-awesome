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
# Warmup Iteration   1: 1.181 ops/ms
Iteration   1: 6.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.541 ops/ms


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
# Warmup Iteration   1: 5.063 ops/ms
Iteration   1: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.452 ops/ms


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
# Warmup Iteration   1: 5.857 ops/ms
Iteration   1: 14.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.153 ops/ms


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
# Warmup Iteration   1: 5.878 ops/ms
Iteration   1: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.267 ops/ms


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.093 ms/op
Iteration   1: 2.068 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.055 ±(99.9%) 0.078 ms/op
Iteration   1: 2.010 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.055 ms/op
Iteration   1: 2.091 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.091 ms/op


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.108 ms/op
Iteration   1: 3.578 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.578 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.085 ms/op
Iteration   1: 2.227 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.764 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   5.575 ms/op
                 createUser·p0.999:  20.719 ms/op
                 createUser·p0.9999: 21.813 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14350
  mean =      2.227 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11167 
    [ 2.500,  5.000) = 3018 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.764 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      5.575 ms/op
     p(99.9000) =     20.719 ms/op
     p(99.9900) =     21.813 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.071 ms/op
Iteration   1: 2.235 ±(99.9%) 0.045 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.052 ms/op
                 existUser·p0.90:   2.699 ms/op
                 existUser·p0.95:   2.969 ms/op
                 existUser·p0.99:   5.927 ms/op
                 existUser·p0.999:  33.522 ms/op
                 existUser·p0.9999: 34.220 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14244
  mean =      2.235 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11725 
    [ 2.500,  5.000) = 2343 
    [ 5.000,  7.500) = 83 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.969 ms/op
     p(99.0000) =      5.927 ms/op
     p(99.9000) =     33.522 ms/op
     p(99.9900) =     34.220 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.095 ms/op
Iteration   1: 2.099 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.460 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   3.346 ms/op
                 getUser·p0.999:  13.086 ms/op
                 getUser·p0.9999: 14.509 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15330
  mean =      2.099 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 352 
    [ 1.250,  2.500) = 11354 
    [ 2.500,  3.750) = 3518 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     13.086 ms/op
     p(99.9900) =     14.509 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.177 ms/op
Iteration   1: 3.034 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.120 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 15.966 ms/op
                 listUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10533
  mean =      3.034 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1006 
    [ 2.500,  3.750) = 8271 
    [ 3.750,  5.000) = 1120 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     15.966 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.541          ops/ms
ClientSimple.existUser                       thrpt         12.452          ops/ms
ClientSimple.getUser                         thrpt         14.153          ops/ms
ClientSimple.listUser                        thrpt          8.267          ops/ms
ClientSimple.createUser                       avgt          2.068           ms/op
ClientSimple.existUser                        avgt          2.010           ms/op
ClientSimple.getUser                          avgt          2.091           ms/op
ClientSimple.listUser                         avgt          3.578           ms/op
ClientSimple.createUser                     sample  14350   2.227 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.764           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.575           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.719           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.813           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.856           ms/op
ClientSimple.existUser                      sample  14244   2.235 ± 0.045   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.657           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.052           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.969           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.927           ms/op
ClientSimple.existUser:existUser·p0.999     sample         33.522           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.220           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.275           ms/op
ClientSimple.getUser                        sample  15330   2.099 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.460           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.346           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.086           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.509           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.286           ms/op
ClientSimple.listUser                       sample  10533   3.034 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.858           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.120           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.303           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.966           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.974           ms/op

Benchmark result is saved to 1717244117069.json
