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
# Warmup Iteration   1: 1.173 ops/ms
Iteration   1: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.493 ops/ms


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
# Warmup Iteration   1: 5.003 ops/ms
Iteration   1: 12.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.287 ops/ms


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
# Warmup Iteration   1: 5.039 ops/ms
Iteration   1: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.894 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ops/ms
Iteration   1: 7.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.221 ops/ms


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.067 ms/op
Iteration   1: 2.022 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.061 ms/op
Iteration   1: 1.874 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.058 ms/op
Iteration   1: 2.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.121 ms/op
Iteration   1: 3.354 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.354 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.086 ms/op
Iteration   1: 2.341 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   2.056 ms/op
                 createUser·p0.90:   2.900 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   13.017 ms/op
                 createUser·p0.999:  26.214 ms/op
                 createUser·p0.9999: 34.641 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13662
  mean =      2.341 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10784 
    [ 2.500,  5.000) = 2623 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =     13.017 ms/op
     p(99.9000) =     26.214 ms/op
     p(99.9900) =     34.641 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 2.869 ±(99.9%) 0.062 ms/op
Iteration   1: 1.936 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   1.868 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   3.042 ms/op
                 existUser·p0.999:  10.264 ms/op
                 existUser·p0.9999: 10.776 ms/op
                 existUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16523
  mean =      1.936 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 14884 
    [ 2.500,  3.750) = 1168 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.042 ms/op
     p(99.9000) =     10.264 ms/op
     p(99.9900) =     10.776 ms/op
     p(99.9990) =     10.797 ms/op
     p(99.9999) =     10.797 ms/op
    p(100.0000) =     10.797 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.171 ms/op
Iteration   1: 2.134 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.034 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  20.250 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15010
  mean =      2.134 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12974 
    [ 2.500,  5.000) = 1909 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =     20.250 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.131 ms/op
Iteration   1: 3.278 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.640 ms/op
                 listUser·p0.50:   3.371 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.084 ms/op
                 listUser·p0.999:  6.278 ms/op
                 listUser·p0.9999: 10.863 ms/op
                 listUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9838
  mean =      3.278 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1236 
    [ 2.500,  3.750) = 6259 
    [ 3.750,  5.000) = 2236 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.084 ms/op
     p(99.9000) =      6.278 ms/op
     p(99.9900) =     10.863 ms/op
     p(99.9990) =     10.863 ms/op
     p(99.9999) =     10.863 ms/op
    p(100.0000) =     10.863 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.493          ops/ms
ClientSimple.existUser                       thrpt         12.287          ops/ms
ClientSimple.getUser                         thrpt         12.894          ops/ms
ClientSimple.listUser                        thrpt          7.221          ops/ms
ClientSimple.createUser                       avgt          2.022           ms/op
ClientSimple.existUser                        avgt          1.874           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.354           ms/op
ClientSimple.createUser                     sample  13662   2.341 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.638           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.056           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.900           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.017           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.214           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.641           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.914           ms/op
ClientSimple.existUser                      sample  16523   1.936 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.629           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.868           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.042           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.264           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.776           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.797           ms/op
ClientSimple.getUser                        sample  15010   2.134 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.034           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.879           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.250           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.775           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.840           ms/op
ClientSimple.listUser                       sample   9838   3.278 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.640           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.371           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.084           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.278           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.863           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.863           ms/op

Benchmark result is saved to 1714673454222.json
