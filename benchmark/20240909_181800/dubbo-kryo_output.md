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
# Warmup Iteration   1: 1.474 ops/ms
Iteration   1: 6.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.105 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.091 ops/ms
Iteration   1: 11.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.898 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.801 ops/ms
Iteration   1: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.106 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.660 ops/ms
Iteration   1: 9.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.025 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.077 ms/op
Iteration   1: 2.101 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ±(99.9%) 0.055 ms/op
Iteration   1: 1.865 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.865 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.260 ±(99.9%) 0.058 ms/op
Iteration   1: 1.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.972 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.098 ms/op
Iteration   1: 3.192 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.192 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ±(99.9%) 0.089 ms/op
Iteration   1: 2.151 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   1.780 ms/op
                 createUser·p0.90:   2.518 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  31.003 ms/op
                 createUser·p0.9999: 33.987 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14862
  mean =      2.151 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13337 
    [ 2.500,  5.000) = 1078 
    [ 5.000,  7.500) = 273 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.518 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     31.003 ms/op
     p(99.9900) =     33.987 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 2.763 ±(99.9%) 0.066 ms/op
Iteration   1: 1.777 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   1.653 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  20.021 ms/op
                 existUser·p0.9999: 21.024 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18001
  mean =      1.777 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17351 
    [ 2.500,  5.000) = 577 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      1.653 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     21.024 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.094 ms/op
Iteration   1: 2.099 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.013 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   4.256 ms/op
                 getUser·p0.999:  14.623 ms/op
                 getUser·p0.9999: 14.983 ms/op
                 getUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15240
  mean =      2.099 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 13192 
    [ 2.500,  3.750) = 1755 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.256 ms/op
     p(99.9000) =     14.623 ms/op
     p(99.9900) =     14.983 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.149 ms/op
Iteration   1: 3.878 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.117 ms/op
                 listUser·p0.999:  17.378 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8327
  mean =      3.878 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 634 
    [ 2.500,  3.750) = 2422 
    [ 3.750,  5.000) = 4842 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.117 ms/op
     p(99.9000) =     17.378 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.105          ops/ms
ClientSimple.existUser                       thrpt         11.898          ops/ms
ClientSimple.getUser                         thrpt         13.106          ops/ms
ClientSimple.listUser                        thrpt          9.025          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.865           ms/op
ClientSimple.getUser                          avgt          1.972           ms/op
ClientSimple.listUser                         avgt          3.192           ms/op
ClientSimple.createUser                     sample  14862   2.151 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.496           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.780           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.518           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.175           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.003           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.987           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.210           ms/op
ClientSimple.existUser                      sample  18001   1.777 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.781           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.653           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.047           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.021           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.024           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.496           ms/op
ClientSimple.getUser                        sample  15240   2.099 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.764           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.013           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.256           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.623           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.983           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.991           ms/op
ClientSimple.listUser                       sample   8327   3.878 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.751           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.117           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.378           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.874           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.874           ms/op

Benchmark result is saved to 1725905603474.json
