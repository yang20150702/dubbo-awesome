# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
Iteration   1: 6.200 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.200 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.369 ops/ms
Iteration   1: 11.613 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.613 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ops/ms
Iteration   1: 7.073 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.073 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.892 ops/ms
Iteration   1: 3.745 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.745 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.003 ±(99.9%) 0.057 ms/op
Iteration   1: 3.278 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.253 ±(99.9%) 0.033 ms/op
Iteration   1: 1.902 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.902 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ±(99.9%) 0.060 ms/op
Iteration   1: 3.293 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.293 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.942 ±(99.9%) 0.276 ms/op
Iteration   1: 7.844 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.880 ±(99.9%) 0.138 ms/op
Iteration   1: 3.043 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.884 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   7.276 ms/op
                 createUser·p0.999:  10.059 ms/op
                 createUser·p0.9999: 10.829 ms/op
                 createUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10677
  mean =      3.043 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 51 
    [ 2.000,  3.000) = 6038 
    [ 3.000,  4.000) = 3873 
    [ 4.000,  5.000) = 496 
    [ 5.000,  6.000) = 79 
    [ 6.000,  7.000) = 18 
    [ 7.000,  8.000) = 56 
    [ 8.000,  9.000) = 22 
    [ 9.000, 10.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      7.276 ms/op
     p(99.9000) =     10.059 ms/op
     p(99.9900) =     10.829 ms/op
     p(99.9990) =     10.830 ms/op
     p(99.9999) =     10.830 ms/op
    p(100.0000) =     10.830 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ±(99.9%) 0.080 ms/op
Iteration   1: 1.751 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.314 ms/op
                 existUser·p0.99:   2.974 ms/op
                 existUser·p0.999:  5.672 ms/op
                 existUser·p0.9999: 9.023 ms/op
                 existUser·p1.00:   9.077 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18273
  mean =      1.751 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 47 
    [ 1.000,  2.000) = 15213 
    [ 2.000,  3.000) = 2832 
    [ 3.000,  4.000) = 134 
    [ 4.000,  5.000) = 13 
    [ 5.000,  6.000) = 21 
    [ 6.000,  7.000) = 3 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.314 ms/op
     p(99.0000) =      2.974 ms/op
     p(99.9000) =      5.672 ms/op
     p(99.9900) =      9.023 ms/op
     p(99.9990) =      9.077 ms/op
     p(99.9999) =      9.077 ms/op
    p(100.0000) =      9.077 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.660 ±(99.9%) 0.131 ms/op
Iteration   1: 2.820 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.740 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.798 ms/op
                 getUser·p0.999:  6.042 ms/op
                 getUser·p0.9999: 7.410 ms/op
                 getUser·p1.00:   7.430 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11430
  mean =      2.820 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 8 
    [1.000, 1.500) = 45 
    [1.500, 2.000) = 337 
    [2.000, 2.500) = 2987 
    [2.500, 3.000) = 4659 
    [3.000, 3.500) = 2145 
    [3.500, 4.000) = 807 
    [4.000, 4.500) = 249 
    [4.500, 5.000) = 109 
    [5.000, 5.500) = 31 
    [5.500, 6.000) = 40 
    [6.000, 6.500) = 11 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.798 ms/op
     p(99.9000) =      6.042 ms/op
     p(99.9900) =      7.410 ms/op
     p(99.9990) =      7.430 ms/op
     p(99.9999) =      7.430 ms/op
    p(100.0000) =      7.430 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 10.546 ±(99.9%) 0.336 ms/op
Iteration   1: 7.331 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   6.971 ms/op
                 listUser·p0.90:   9.488 ms/op
                 listUser·p0.95:   10.716 ms/op
                 listUser·p0.99:   18.298 ms/op
                 listUser·p0.999:  26.043 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4358
  mean =      7.331 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 279 
    [ 5.000,  7.500) = 2544 
    [ 7.500, 10.000) = 1202 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      6.971 ms/op
     p(90.0000) =      9.488 ms/op
     p(95.0000) =     10.716 ms/op
     p(99.0000) =     18.298 ms/op
     p(99.9000) =     26.043 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.200          ops/ms
Client.existUser                       thrpt         11.613          ops/ms
Client.getUser                         thrpt          7.073          ops/ms
Client.listUser                        thrpt          3.745          ops/ms
Client.createUser                       avgt          3.278           ms/op
Client.existUser                        avgt          1.902           ms/op
Client.getUser                          avgt          3.293           ms/op
Client.listUser                         avgt          7.844           ms/op
Client.createUser                     sample  10677   3.043 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          0.997           ms/op
Client.createUser:createUser·p0.50    sample          2.884           ms/op
Client.createUser:createUser·p0.90    sample          3.817           ms/op
Client.createUser:createUser·p0.95    sample          4.129           ms/op
Client.createUser:createUser·p0.99    sample          7.276           ms/op
Client.createUser:createUser·p0.999   sample         10.059           ms/op
Client.createUser:createUser·p0.9999  sample         10.829           ms/op
Client.createUser:createUser·p1.00    sample         10.830           ms/op
Client.existUser                      sample  18273   1.751 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.743           ms/op
Client.existUser:existUser·p0.50      sample          1.698           ms/op
Client.existUser:existUser·p0.90      sample          2.134           ms/op
Client.existUser:existUser·p0.95      sample          2.314           ms/op
Client.existUser:existUser·p0.99      sample          2.974           ms/op
Client.existUser:existUser·p0.999     sample          5.672           ms/op
Client.existUser:existUser·p0.9999    sample          9.023           ms/op
Client.existUser:existUser·p1.00      sample          9.077           ms/op
Client.getUser                        sample  11430   2.820 ± 0.018   ms/op
Client.getUser:getUser·p0.00          sample          0.807           ms/op
Client.getUser:getUser·p0.50          sample          2.740           ms/op
Client.getUser:getUser·p0.90          sample          3.539           ms/op
Client.getUser:getUser·p0.95          sample          3.846           ms/op
Client.getUser:getUser·p0.99          sample          4.798           ms/op
Client.getUser:getUser·p0.999         sample          6.042           ms/op
Client.getUser:getUser·p0.9999        sample          7.410           ms/op
Client.getUser:getUser·p1.00          sample          7.430           ms/op
Client.listUser                       sample   4358   7.331 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.109           ms/op
Client.listUser:listUser·p0.50        sample          6.971           ms/op
Client.listUser:listUser·p0.90        sample          9.488           ms/op
Client.listUser:listUser·p0.95        sample         10.716           ms/op
Client.listUser:listUser·p0.99        sample         18.298           ms/op
Client.listUser:listUser·p0.999       sample         26.043           ms/op
Client.listUser:listUser·p0.9999      sample         28.115           ms/op
Client.listUser:listUser·p1.00        sample         28.115           ms/op
