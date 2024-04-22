# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.431 ops/ms
Iteration   1: 6.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.475 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ops/ms
Iteration   1: 12.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.127 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ops/ms
Iteration   1: 12.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.821 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ops/ms
Iteration   1: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.226 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.074 ms/op
Iteration   1: 2.312 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.423 ±(99.9%) 0.057 ms/op
Iteration   1: 1.895 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.895 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ±(99.9%) 0.060 ms/op
Iteration   1: 2.066 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.098 ms/op
Iteration   1: 3.840 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ±(99.9%) 0.087 ms/op
Iteration   1: 2.221 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  16.322 ms/op
                 createUser·p0.9999: 16.949 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14401
  mean =      2.221 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 11975 
    [ 2.500,  3.750) = 1785 
    [ 3.750,  5.000) = 256 
    [ 5.000,  6.250) = 146 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     16.322 ms/op
     p(99.9900) =     16.949 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ±(99.9%) 0.071 ms/op
Iteration   1: 2.061 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   1.985 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 16.935 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15504
  mean =      2.061 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 14347 
    [ 2.500,  3.750) = 784 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     16.935 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.564 ±(99.9%) 0.137 ms/op
Iteration   1: 1.997 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   4.052 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 19.667 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16126
  mean =      1.997 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 14924 
    [ 2.500,  3.750) = 881 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.052 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     19.667 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ±(99.9%) 0.134 ms/op
Iteration   1: 3.213 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.198 ms/op
                 listUser·p0.999:  28.776 ms/op
                 listUser·p0.9999: 32.670 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9817
  mean =      3.213 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1144 
    [ 2.500,  5.000) = 8471 
    [ 5.000,  7.500) = 141 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.198 ms/op
     p(99.9000) =     28.776 ms/op
     p(99.9900) =     32.670 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.475          ops/ms
ClientSimple.existUser                       thrpt         12.127          ops/ms
ClientSimple.getUser                         thrpt         12.821          ops/ms
ClientSimple.listUser                        thrpt          8.226          ops/ms
ClientSimple.createUser                       avgt          2.312           ms/op
ClientSimple.existUser                        avgt          1.895           ms/op
ClientSimple.getUser                          avgt          2.066           ms/op
ClientSimple.listUser                         avgt          3.840           ms/op
ClientSimple.createUser                     sample  14401   2.221 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.821           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.207           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.322           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.949           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.007           ms/op
ClientSimple.existUser                      sample  15504   2.061 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.654           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.985           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.383           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.564           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.935           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  16126   1.997 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.052           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.416           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.667           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.988           ms/op
ClientSimple.listUser                       sample   9817   3.213 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.919           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.896           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.198           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.776           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.670           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.670           ms/op

Benchmark result is saved to 1713746362674.json
