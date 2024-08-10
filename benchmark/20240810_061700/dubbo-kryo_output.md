# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.641 ops/ms
Iteration   1: 7.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.617 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.248 ops/ms
Iteration   1: 13.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.614 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 11.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.776 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.135 ops/ms
Iteration   1: 8.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.747 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.067 ms/op
Iteration   1: 2.017 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ±(99.9%) 0.049 ms/op
Iteration   1: 1.939 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.939 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.258 ±(99.9%) 0.056 ms/op
Iteration   1: 2.057 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.090 ms/op
Iteration   1: 3.543 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.543 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.627 ±(99.9%) 0.105 ms/op
Iteration   1: 2.216 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.808 ms/op
                 createUser·p0.99:   9.093 ms/op
                 createUser·p0.999:  28.218 ms/op
                 createUser·p0.9999: 29.605 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14429
  mean =      2.216 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12816 
    [ 2.500,  5.000) = 1334 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.808 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     28.218 ms/op
     p(99.9900) =     29.605 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ±(99.9%) 0.061 ms/op
Iteration   1: 1.782 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.245 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.376 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  27.623 ms/op
                 existUser·p0.9999: 28.171 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17934
  mean =      1.782 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17241 
    [ 2.500,  5.000) = 564 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.245 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     27.623 ms/op
     p(99.9900) =     28.171 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ±(99.9%) 0.074 ms/op
Iteration   1: 1.940 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.602 ms/op
                 getUser·p0.99:   3.243 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 11.557 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16472
  mean =      1.940 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 408 
    [ 1.250,  2.500) = 14568 
    [ 2.500,  3.750) = 1346 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.602 ms/op
     p(99.0000) =      3.243 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     11.557 ms/op
     p(99.9990) =     11.600 ms/op
     p(99.9999) =     11.600 ms/op
    p(100.0000) =     11.600 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ±(99.9%) 0.107 ms/op
Iteration   1: 3.541 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.653 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   5.877 ms/op
                 listUser·p0.999:  24.403 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9057
  mean =      3.541 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 876 
    [ 2.500,  5.000) = 7917 
    [ 5.000,  7.500) = 219 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.877 ms/op
     p(99.9000) =     24.403 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.617          ops/ms
ClientSimple.existUser                       thrpt         13.614          ops/ms
ClientSimple.getUser                         thrpt         11.776          ops/ms
ClientSimple.listUser                        thrpt          8.747          ops/ms
ClientSimple.createUser                       avgt          2.017           ms/op
ClientSimple.existUser                        avgt          1.939           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          3.543           ms/op
ClientSimple.createUser                     sample  14429   2.216 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.556           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.808           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.093           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.218           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.605           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.983           ms/op
ClientSimple.existUser                      sample  17934   1.782 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.245           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.163           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.555           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.623           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.171           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.639           ms/op
ClientSimple.getUser                        sample  16472   1.940 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.602           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.243           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.557           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.600           ms/op
ClientSimple.listUser                       sample   9057   3.541 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.653           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.877           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.403           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.100           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.100           ms/op

Benchmark result is saved to 1723270361163.json
