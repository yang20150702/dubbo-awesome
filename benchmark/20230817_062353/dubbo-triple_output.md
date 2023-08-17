# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.713 ops/ms
# Warmup Iteration   2: 3.568 ops/ms
# Warmup Iteration   3: 7.142 ops/ms
Iteration   1: 7.599 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 8.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.790 ±(99.9%) 3.933 ops/ms [Average]
  (min, avg, max) = (7.599, 7.790, 8.024), stdev = 0.216
  CI (99.9%): [3.857, 11.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.268 ops/ms
# Warmup Iteration   2: 6.836 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 8.081 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 8.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.196 ±(99.9%) 2.685 ops/ms [Average]
  (min, avg, max) = (8.081, 8.196, 8.362), stdev = 0.147
  CI (99.9%): [5.511, 10.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 6.608 ops/ms
# Warmup Iteration   3: 8.018 ops/ms
Iteration   1: 7.719 ops/ms
Iteration   2: 8.418 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.043 ±(99.9%) 6.425 ops/ms [Average]
  (min, avg, max) = (7.719, 8.043, 8.418), stdev = 0.352
  CI (99.9%): [1.618, 14.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.112 ops/ms
# Warmup Iteration   2: 6.021 ops/ms
# Warmup Iteration   3: 6.712 ops/ms
Iteration   1: 6.684 ops/ms
Iteration   2: 6.950 ops/ms
Iteration   3: 6.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.846 ±(99.9%) 2.591 ops/ms [Average]
  (min, avg, max) = (6.684, 6.846, 6.950), stdev = 0.142
  CI (99.9%): [4.255, 9.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.838 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.006 ms/op
Iteration   1: 3.904 ±(99.9%) 0.006 ms/op
Iteration   2: 4.063 ±(99.9%) 0.006 ms/op
Iteration   3: 3.962 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.977 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.904, 3.977, 4.063), stdev = 0.080
  CI (99.9%): [2.514, 5.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.019 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.003 ms/op
Iteration   1: 3.901 ±(99.9%) 0.005 ms/op
Iteration   2: 3.877 ±(99.9%) 0.006 ms/op
Iteration   3: 3.841 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.873 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (3.841, 3.873, 3.901), stdev = 0.030
  CI (99.9%): [3.326, 4.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.327 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.005 ms/op
Iteration   1: 4.009 ±(99.9%) 0.004 ms/op
Iteration   2: 3.962 ±(99.9%) 0.003 ms/op
Iteration   3: 4.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.011 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.962, 4.011, 4.063), stdev = 0.050
  CI (99.9%): [3.095, 4.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.684 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.583 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.008 ms/op
Iteration   1: 4.696 ±(99.9%) 0.010 ms/op
Iteration   2: 4.547 ±(99.9%) 0.012 ms/op
Iteration   3: 4.575 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.606 ±(99.9%) 1.443 ms/op [Average]
  (min, avg, max) = (4.547, 4.606, 4.696), stdev = 0.079
  CI (99.9%): [3.163, 6.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.902 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.019 ms/op
Iteration   1: 4.026 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  23.610 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 4.057 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  26.712 ms/op
                 createUser·p0.9999: 31.953 ms/op
                 createUser·p1.00:   34.800 ms/op

Iteration   3: 4.041 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  14.828 ms/op
                 createUser·p0.9999: 32.282 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237460
  mean =      4.042 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 416 
    [ 2.500,  5.000) = 217852 
    [ 5.000,  7.500) = 16141 
    [ 7.500, 10.000) = 1989 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     23.676 ms/op
     p(99.9900) =     31.826 ms/op
     p(99.9990) =     33.674 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.085 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  22.651 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 3.918 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   8.323 ms/op
                 existUser·p0.999:  14.717 ms/op
                 existUser·p0.9999: 33.198 ms/op
                 existUser·p1.00:   36.176 ms/op

Iteration   3: 3.795 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.829 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  27.660 ms/op
                 existUser·p0.9999: 30.675 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250419
  mean =      3.834 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 384 
    [ 2.500,  5.000) = 239444 
    [ 5.000,  7.500) = 7796 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 659 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     32.043 ms/op
     p(99.9990) =     34.242 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.806 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.016 ms/op
Iteration   1: 4.056 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.991 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.893 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 26.185 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   8.176 ms/op
                 getUser·p0.999:  16.954 ms/op
                 getUser·p0.9999: 27.421 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 4.040 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  28.934 ms/op
                 getUser·p0.9999: 35.591 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239880
  mean =      4.002 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 225667 
    [ 5.000,  7.500) = 10677 
    [ 7.500, 10.000) = 2305 
    [10.000, 12.500) = 605 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.103 ms/op
     p(99.9000) =     22.691 ms/op
     p(99.9900) =     32.936 ms/op
     p(99.9990) =     36.084 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.544 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.499 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.019 ms/op
Iteration   1: 4.717 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  25.926 ms/op
                 listUser·p0.9999: 31.996 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   2: 4.733 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 22.502 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.646 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 19.572 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204303
  mean =      4.698 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 173987 
    [ 5.000,  7.500) = 24197 
    [ 7.500, 10.000) = 4568 
    [10.000, 12.500) = 950 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     30.521 ms/op
     p(99.9990) =     32.599 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.790 ± 3.933  ops/ms
ClientPb.existUser                       thrpt       3   8.196 ± 2.685  ops/ms
ClientPb.getUser                         thrpt       3   8.043 ± 6.425  ops/ms
ClientPb.listUser                        thrpt       3   6.846 ± 2.591  ops/ms
ClientPb.createUser                       avgt       3   3.977 ± 1.463   ms/op
ClientPb.existUser                        avgt       3   3.873 ± 0.547   ms/op
ClientPb.getUser                          avgt       3   4.011 ± 0.917   ms/op
ClientPb.listUser                         avgt       3   4.606 ± 1.443   ms/op
ClientPb.createUser                     sample  237460   4.042 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.676           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.826           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  250419   3.834 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.815           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.043           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.176           ms/op
ClientPb.getUser                        sample  239880   4.002 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.691           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  204303   4.698 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.997           ms/op
